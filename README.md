# VideoEncoderBot
 a telegram bot for encoding videos in h264 format.


### Configuration
Add values in environment variables or add them in [config.env.example](/VideoEncoder/config.env.example) and rename file to `config.env`.

**Basics**
- `API_ID` - Get it by creating an app on [https://my.telegram.org](https://my.telegram.org)
- `API_HASH` - Get it by creating an app on [https://my.telegram.org](https://my.telegram.org)
- `BOT_TOKEN` - Get it by creating a bot on [https://t.me/BotFather](https://t.me/BotFather)

**Authorization**
- `SUDO_USERS` - Chat identifier of the sudo user. For multiple users use space as seperator.

**Encode Settings**
- `RESOLUTION` - Keep 360,480,720,1080
- `PRESET` - Keep f (fast),vf (Veryfast),sf (Superfast)
- `TUNE` - Keep film or animation
- `AUDIO` - Keep opus or aac
- `CRF` - Keep anything from 25 to 30

**Optional**
- `DOC_THUMB` - (Optional) Thumbnail for document 
- `UPLOAD_AS_DOC` - (Optional) Uploads Video as doc if `1` else `0`.
- `DOWNLOAD_DIR` - VideoEncoder/utils/downloads/
- `ENCODE_DIR` - VideoEncoder/utils/encodes/

### Deploy Now:

### Deploy your bot on `Heroku`

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/NikhilBakugo/Video-Encoder-Bot)

### Deploy your bot on `Okteto`
  
[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com)


```
pip3 install --no-cache-dir -r requirements.txt
bash run.sh
```

### Credits
- [ShannonScott](https://gist.github.com/ShannonScott) for [transcode_h265.py](https://gist.github.com/ShannonScott/6d807fc59bfa0356eee64fad66f9d9a8)
- [viperadnan-git](https://github.com/viperadnan-git/video-encoder-bot) for queue etc.
- [Nikhil_Sequeira](https://github.com/NikhilBakugo/VideoEncoder-bot) for [Making it to deploy through Okteto and Heroku]

### Copyright & License
- Copyright &copy; 2021 &mdash; [WeebTime](https://github.com/WeebTime)
- Licensed under the terms of the [GNU AFFERO GENERAL PUBLIC LICENSE](./LICENSE)
