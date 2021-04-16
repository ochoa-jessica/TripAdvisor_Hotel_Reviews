### TripAdvisor Hotel Reviews WordCloud

### What is WordCloud?
<p>Wordcloud is an amazing data exploratory tool for reviewing the most important thematic words in harmony from a group of words within a context like customer reviews. In simple terms, it is a picture consisting of a group of words where the size of each word represents frequency or importance. The bigger and bolder the words appears, the more often it's mentioned within a given text.</p>

### Data
<p>For the purpose of exploring ways to customize WordCloud I have used Trip Advisor Hotel Reviews dataset.</p>

### Simple WordCloud of TripAdvisor Hotel Reviews
![Image of WordCloud Of TripAdvisor Hotel Review](Hotel_Reviews_WordClouds/SImple_WordCloud.png)

### Masking
<p>One way to make your word cloud visually stunning is to add a mask. A mask is an image you can use to change the shape of your word cloud. We can manipulate the mask very easily with the mask parameter when we instantiate the WordCloud object. Once the perfect image has been choosen we can use the Image function from the PIL library and numpy to get it into the correct format for the WordCloud object.</p>

<p>Here is our final word cloud...</p>
    
![Image of WordCloud Masking](Hotel_Reviews_WordClouds/Masking.png)

### Adjusting Color
<p>We can also adjust the colors used in the word cloud. The color format used is the HSL format (hue, saturation, lightness).</p>

![Image of WordCloud Custom Color](Hotel_Reviews_WordClouds/Custom_Color.png)

> Essentially WordCloud tool comes in handy for text analytics and is quite informative & visually appealing.