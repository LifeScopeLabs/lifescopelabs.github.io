# lifescope-ai

This is a suite of tools for reporting and machine learning from LIFESCOPE data. Reporting is focused on building approachable dashboard visualizations and infographics.

Machine learning models based on LIFESCOPE data are focused on behavior modeling, correlation, prediction, suggestion, and impersonation.

## Reporting

Create infographics and reports for lifescope users based on their data.

Examples:
![infographics1][infographics1]

![infographics2][infographics2]

### Dependences

- [Tau Charts](https://www.taucharts.com/)

## Machine Learning

#### Conversational Agents

Examples:
[CakeChat Framework](https://cakechat.replika.ai/) 

Impersonation Ideas:
- **Persona-based model**. Condition responses on a certain author of messages (User ID) to make responses lexically similar to them and mimic someone’s linguistic style in a conversation. Use new or pre-trained models to run a chatbot that maintains a conversation in a certain emotional state. 
- **Emotional chatting machine** with your own set of emotions. There are so many emotions that you can use as condition labels in your dataset. CakeChat only uses five basic emotions (anger, sadness, joy, fear and neutral). 
- **Topic-centric model**. Instead of emotions, you can use a set of topics that will condition the model’s responses. As a result, you can build an agent that sticks to a given topic in a conversation. For example, you can build a model that talks about weather, food, kids or mortgage at any given moment.

### Geolocation Based Models

Prediction and anomaly detection based on location history.

![heatmap]

#### Examples:
- [Numenta Geospatioal](https://numenta.com/assets/pdf/whitepapers/Geospatial%20Tracking%20White%20Paper.pdf)
- [Numenta Geospatioal Github Example](https://github.com/numenta/nupic.geospatial)

[heatmap]:https://lifescopelabs.github.io/assets/maps/heat-map.png
[infographics1]:https://lifescopelabs.github.io/assets/screenshots/infographics1.png
[infographics2]:https://lifescopelabs.github.io/assets/screenshots/infographics2.png
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAzMDE4NzE2M119
-->