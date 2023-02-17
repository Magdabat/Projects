
**The Idea:**
As a huge Star Trek fan, I'm working on a model that can predict which series a picture comes from. You take a snap of the screen, upload it and the model tells you which Star Trek series you are looking at.
In the current version, I focus on four series:
- The Next Generation
- Discovery
- Deep Space Nine
- Voyager

**The Technology:**
Keras and convolutional neural networks

**The Training Data:**
I'm scraping pictures from IMDB, which has an image collection for various TV shows and movies. This also makes the idea scalable with different movies / TV-shows (all you need is the movies id)

**Problematisation:**
- The pictures from IMDB are not ideal, as they include portraits of actors, backstage shots, and posters. 
- Additionally, IMDB primarily focuses on main actors and objects (starships, props). So, if somebody takes shot of something that is not in the training data, it will not be recognised properly.
- Another challenge is that some of the series are quite similar. In particularly The Next Generation and Deep Space Nine, which share many actors.

*Now, let us see what Keras and CNN are capable of:).*
