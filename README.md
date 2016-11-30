# youtube-python
===================
#### Python - Youtube Data API v3

**youtube-python** is a simple client for youtube api. It uses [Youtube Data API v3](https://developers.google.com/youtube/v3/).

## Installation
``` 
sudo pip install youtube-python
```

## Using
```python
from youtube import YouTube
api = youtube.YouTube(api_key='')
```

## References https://developers.google.com/youtube/v3/docs/videos/list
```python
video = api.get('videos', id='B7FJV9KIn58')
```

## References https://developers.google.com/youtube/v3/docs/channels/list
```python
channel = api.get('channels', id='UCLFZ5qAH-l_WiRd_EOzX2og')
```


## Contributing
[https://github.com/rohitkhatri/youtube-python](https://github.com/rohitkhatri/youtube-python)

## Youtube Data API v3
[Youtube Data API v3 Doc](https://developers.google.com/youtube/v3/)
