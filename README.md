# BrainSong

### Description: 
This is a song guessing game designed to help make brainstorming process fun and fast. It uses Postman API tool as a alternative backend, and uses Echo Alexa to provide the voice based user interface.

### Game Rules:
1. Alexa plays a song for 30 sec.
2. Players guess the name of the song played.
3. Alexa takes the voice input of the song name. If correct, Alexa prompts the player to speak about an `Action item` and saves it to an `Action list`. If incorrect, Alexa will play the song again and if failed still or passed by the players Alexa will move to the next song.
4. After Alexa gathered enough `Action items`, it will send the `Action list` to a designated Slack channel.

### Implementation:
* Build a Postman collection that can fetch songs from a online music service.
  There are several music services to select, with Spotify being a top pick.
* Build an Alexa Skill to be able to interact with the players.
* Build a Postman collection that can post results to Slack. 

Andrew contributed a link to http://static.echonest.com/enspex/ which points to a set of Echo Nest and Spotify APIs. 
