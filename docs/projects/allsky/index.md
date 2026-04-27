# Using Machine Learning with All Sky Camera Observations
The night sky is a very dynamic place! Clouds, airglow, humidity, precipitation, and many other factors may affect how well a telescope on the ground can capture observations of objects far out in space. Astronomers must constantly monitor how these conditions change. 

The Rothney Astrophysical Observatory (RAO) is a research facility located southwest of Calgary, Alberta. It hosts three large telescopes, but also a number of supporting instruments that enable observers to make informed decisions and protect expensive equipment. One such device is an all sky camera that points straight up and takes pictures of the entire sky at once using a fish eye lens. At the RAO, it takes a picture every four minutes, no matter the time of day or sky conditions, and saves it to an archive that now has nearly 10 years worth of pictures. 

While weather conditions are critical for astronomers, they are not easily quantifiable. It is most economically and scientifically efficient to nterpreting the risk of weather is therefore challenging, and subject to human bias. For instance, it may be safe to operate the telescopes in 10% cloud coverage, but not 50%. 

In this work, I created a machine learning framework to classify the weather conditions in all sky images to enable data-driven, quantitative atmospheric classification. Such information can empower astronomers to make risk-informed choices!



The figure below shows an example of how an early version of the algorithm classified such images!

![All Sky](./media/AllSkyAI.png "All Sky")

