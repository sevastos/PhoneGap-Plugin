# Publisher Object

The Publisher object provides information about the publishing stream. Calling the TB.initPublisher() method creates a Publisher object.

## Properties

**id** (String) — The ID of the DOM element through which the Publisher stream is displayed

**session** (Session) — The Session to which the Publisher is publishing a stream. If the Publisher is not publishing a stream to a Session, this property is set to null.

**replaceElementId** (String) — The ID of the DOM element that was replaced when the Publisher video stream was inserted.

*Note*: Publisher properties should only be used as read-only entities.


## Methods

[publishAudio()](#publishAudio)  
[publishVideo()](#publishVideo)  


<a name="publishAudio"></a>
### publishAudio( state:Boolean )

Example Code:
```javascript
publisher.publishAudio(false); // Stop publishing audio (mute)
publisher.publishAudio(true);  // Continue publishing audio (by default true)
```

Changes the publishing state of Audio.

#### Parameters

**state** (Boolean) — This boolean identifying the state of publishing.


<a name="publishVideo"></a>
### publishVideo( state:Boolean )

Example Code:
```javascript
publisher.publishVideo(false); // Stop publishing video (mute)
publisher.publishVideo(true);  // Continue publishing video (by default true)
```

Changes the publishing state of Video.

#### Parameters

**state** (Boolean) — This boolean identifying the state of publishing.
