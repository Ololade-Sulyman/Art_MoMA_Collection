# Art MoMA Collection

### Project Objective

This data analysis aims to provide insights into the Museum of Modern Art (MoMA) Collection. By analyzing various aspect of the data, we seek to identify the trends, most featured artists, and how modern is the collection.

### Data Source

- https://mavenanalytics.io/data-playground

The primary dataset used for this project is "Artworks.csv" file, containing detailed information of Art MoMA Collection

### Tools

- Excel [Download here](https://microsoft.com)
- Jupyter Nootbook [Download here](https://jupyter.org/.)

### Process 

- Data loading and Inspection
- Verify data for any missing values and anomalies, and sort out the same.
- Make sure data is consistent and clean with respect to data type, data format and values used


### Exploratory Data Analysis

EDA involved exploring the Art (MoMA) Collection dataset to answer the key questions

1.  Which artists are featured the most
2.  Types of artworks that are most common 
3.  How modern are the artworks at the Museum
4.  Are there any trends in the dates of acquisition

### Data Analysis

~~~python
modern_threshold = 100
df['modern'] = df['Age']<= modern_threshold
~~~~


### project insight

The analysis results are summarized as follows

- Ludwig Mies van der Rohe is the most featured Atists, featured for 13752 periods 
- Photograph is the most common Artwork
- Using modern threshold of 100 years of artworks at the Museum as standard, the Art MoMA Collection has 30 years age Artwork collection and as well as 1 year age Artwork 
  collection which show that the Artworks are modern. 
- Month of October have highest date of acquisition while August is the least. 




<img width="553" alt="Screenshot Arworks" src="https://github.com/user-attachments/assets/64fcdb69-9ba2-4091-9af3-ccd21a119d7b" />


### Conclusion

Start by determining the theme or focus of the collection. Whether it's contemporary art, abstract expressionism, or works by emerging artists, having a clear vision will guide artist acquisitions.

### Reference

[Stackoverflow](https://stack,com)
