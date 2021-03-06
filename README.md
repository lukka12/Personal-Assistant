# đ§ Calls Music 2 â The first open-source project based on [PyTgCalls](https://github.com/pytgcalls/pytgcalls)

## âī¸ Requirements

- FFmpeg
- Node.JS 15+
- Python 3.7+

## đ Deployment

### đ  Config

Copy `example.env` to `.env` and fill it with your credentials.

### â¨ The good way

1. Install Python requirements:
   ```bash
   pip install -U -r requirements.txt
   ```
2. Run:
   ```bash
   python -m callsmusic
   ```

### đŦ Docker

1. Build:
   ```bash
   docker build -t musicplayer .
   ```
2. Run:
   ```bash
   docker run --env-file .env musicplayer
   ```

### đĩ Heroku

[Click here](https://heroku.com/deploy?template=https://github.com/callsmusic/callsmusic-2_heroku/)

## âšī¸ Commands

| Command | Description                                  |
| ------- | -------------------------------------------- |
| /play   | play the replied audio file or YouTube video |
| /pause  | pause the audio stream                       |
| /resume | resume the audio stream                      |
| /skip   | skip the current audio stream                |
| /stop   | clear the queue and stop the audio stream    |

## đ License

### GNU Affero General Public License v3.0

[Read more](https://www.gnu.org/licenses/#AGPL)
