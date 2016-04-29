# nyc-react-meetup-message-board

Demo code from the NYC React Meetup on April 28th, 2016.

## Installation

```bash
git clone git@github.com:eddiezane/nyc-react-meetup-message-board.git
cd nyc-react-meetup-message-board
npm install
```

To get the SMS bit working sign up for a free [Twilio account](https://twilio.com/try-twilio).

Start up [ngrok](https://ngrok.com/) and point your [Twilio Phone Number](https://www.twilio.com/user/account/phone-numbers/incoming) at your ngrok URL.


## Usage

Start the app:

```bash
node .
```

Start [ngrok](https://ngrok.io) in a separate shell:

```bash
ngrok http 3000
```