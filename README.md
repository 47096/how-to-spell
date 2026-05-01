# Spell A Word

> How to spell ... ?

Kids ask "how do you spell [word]?" a hundred times a day. In the car. At the dinner table. When you're busy. It's not annoying because you don't care — it's annoying because you can't always drop everything. This app gives them the answer on their own. Tap the button, say the word, see the spelling. Done.

## Use Cases

**1. Homework time**
Your kid is writing a sentence and gets stuck on a word. Instead of yelling from the other room, they tap the mic, say the word, and get the spelling instantly. They stay in the flow. You stay sane.

**2. Road trips**
"How do you spell 'dinosaur'?" for the fifth time in twenty minutes. Hand them the phone. Problem solved for the rest of the drive.

**3. Bedtime reading**
Your kid finds a new word in their book and wants to know how to spell it. No need to stop reading. Just tap, say, see.

## How It Works

1. Tap the microphone button
2. Say "how to spell [word]" (or just say the word)
3. See the spelling on screen
4. Tap anywhere to try another word

That's it. No accounts. No settings. No distractions.

## Why This Exists

Most spelling apps are bloated. They want your email, your kid's age, a subscription, and twenty minutes of setup before your child can do the one thing they need: find out how to spell a word. This app is a single HTML file. It works on any phone with a browser. No backend, no tracking, no ads. Just a button and a word.

## Tech

- Vanilla HTML, CSS, JavaScript — no frameworks, no dependencies
- Web Speech API for voice recognition
- Static site — deployable anywhere (GitHub Pages, Netlify, a USB stick)
- Works on iOS Safari, Android Chrome, and desktop browsers

## Running Locally

```bash
# clone the repo
git clone https://github.com/wsamuelw/spell-a-word.git
cd spell-a-word

# open in browser
open index.html
```

That's it. No build step. No `npm install`. Just open the file.

## Contributing

PRs welcome. Keep it simple — this app works because it does one thing. If your change adds complexity, open an issue first and let's talk about it.

## License

MIT
