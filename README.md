[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/MilitaryLotus30/MalFinderTM/)
[![NoTextToSpeech](https://dcbadge.vercel.app/api/server/ntts)](https://discord.gg/ntts)

# MalFinder™

MalFinder™ is a bot that has the ability to automatically scan the given links and files for malware using VirusTotal, making it easy and simple.

## Warning ⚠️

VirusTotal does not have a 100% accuracy all of the time. False positives and false negatives can occur so always stay vigilant and cautious.

## Getting Started

This bot uses VirusTotal's API to scan your links or files automatically inside Discord. You heard it right! No longer do you need to leave Discord. Just send a link or file anywhere the bot can read messages and it'll start getting the scanned results to you as soon as it can. The bot will log all it's scanned files, links and errors into a file named log.txt and will print them out aswell.

### Installing

You will need to host the bot as we do not provide hosting as of now. We recommend using a Linux self hosted or cloud server. [Microsoft Azure](<https://azure.microsoft.com/en-us/free/search/>) is a good way to start with 12 free months of hosting services.

Make sure you have Python 3.xx installed before running this code. Copy and paste the code below in any bash supported terminal environment. If you do not know what that is then just open your preferred terminal of choice.

```bash
git clone https://github.com/MilitaryLotus30/MalFinderTM
pip install requirements.txt
python3 main.py
```

Then open `main.py` with a text editor of your choice and put in the details for your VirusTotal API key and your Discord bot Application Token of your chosen bot.

[How to get your VirusTotal API key](<https://youtu.be/9ftKViq71eQ>)

[How to get your Discord bot Application Token/Create a bot and invite to your server. Make sure to give it administrator permissions so that it can monitor any channel](<https://youtu.be/4XswiJ1iUaw>)

## Running the Tests

Simply send a link or file in any of the channels that the bot has access to and it will scan the files or website for malware and provide the scan results with the VirusTotal link of the scan.

### Sample Tests

If you're worried about downloading a file or clicking on a link, this bot can help you!

(placeholder of image of the bot in action)

## Contributing
[![Discord Presence](https://lanyard.cnrad.dev/api/:id)](https://discord.com/users/:id)

Adding usernames of contributors here later.

## License

This project is licensed under the [CC0 1.0 Universal](LICENSE.md) Creative Commons License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- This bot was created for a hackathon event held on NTTS's server.
- A team of 4 people helped on this project.
- Wish us luck!

<3
