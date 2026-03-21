---

title: "How I Built This Site (With AI, Hugo, and Zero Patience)"
date: 2026-03-21
summary: "The story of how I vibecoded a custom Hugo theme from scratch with ChatGPT, Gemini, and Claude."
tags: ["meta", "writing", "ai", "web-dev"]


---
So, this site exists because nothing else felt like me.

I had an academic Hugo theme before, specifically, the Wowchemy Hugo Academic theme (https://github.com/ioiototm/ioiototm.github.io-older-but-newer (yes, this is classic naming scheme)). It worked, but it felt like wearing someone else's clothes. I'm not just a researcher. I make games, music, art, weird experiments, and I needed a place that could hold all of that without feeling like five different sites taped together.

Around November 2025 I was chatting with ChatGPT and asked it to suggest some Hugo themes for that conundrum. It listed a bunch, but none of them really fit. It either felt too minimal, too formal, too bloggy. And then it hit me, why not just build one from scratch? I don't really have the patience or the web dev knowledge to do that the normal way (I am sure I can do it, given enough time though). But with AI I could describe what I wanted and just go fast, break things, whatever the saying was. So that's what I did.

## How it actually went

ChatGPT created the initial skeleton - after a quick ideation of what I envisioned, it created the basic structure. Then I realised that Github Copilot in VS Code is perfect for this, as it can edit stuff directly on my PC. I used Gemini back then, as it seemed like a very capable model.

Some of the loop was like this: I have a problem, and I need a solution. So, I ask for ideas, with some context that I seed in, it lists a few, something sparks my curiosity or imagination, and then I start explaining how I'm imagining it. It builds something, I look at it, yes or no, change this, change that. Over and over. Mostly it was just fun? Like having a collaborator who doesn't get tired of you going "actually, no, go back". And seeing the site come together like that, it was really exciting. "Oh, how about a terminal at the bottom, as I am a developer and that would be fun?", "Oh wait, you know what sounds good? What if each mode is colour coded, and then I can blend the colours when I have multiple modes on one card?", "Actually, I want a little badge on the game cards, like a transform gizmo, that would be cool!", etc.

## Cards and colours

I really like how the content is structured on the website. Everything is a "card" and each card can have multiple modes. A project can be tagged as both code and game, or music and art, or whatever combination. Each mode has its own colour, and when you combine them the card's border blends between those colours. Two modes, two colours blending into each other. Same with three or more (although, I don't think I have tested it with more than three).

Each mode also has its own visual "gimmick" on the card:

- **Code** gets line numbers down the side (01, 02, 03...), just like a code editor
- **Game** gets a transform badge in the corner (like Unity)
- **Art** gets a dashed selection rectangle on the edges, like in Photoshop or Clip Studio Paint (which is my main art software)
- **Music** gets little sound bars
- **Research** gets a "FIG. 1" label, like a proper paper figure
- **Writing** gets a blinking cursor

And they combine. A card tagged as code and game will have line numbers AND a transform badge at the same time. Just go to the main page and look at the feed, you'll see what I mean.


The colour blending on the outlines almost broke me though. I kept telling the AI "it needs to blend smoothly" and it would do something, and I'd go "no, that's not blending, look at it", and then it would try again and go "ok fixed!" and I'd look at it and... still not blending. This went back and forth for longer than I'd like to admit. But it still was fun in a way. Normally, I would leave it at "good enough" and move on, but with AI I felt like I could get the wording right, or explain it in a way that it finally understood, and then I could have the exact thing I wanted. And of course, I do also go and change the code manually sometimes, when it's something visual and I have to change the CSS.

## On the AI thing

Without AI, this site and theme simply would not exist. I didn't have the frontend knowledge or, frankly, the patience to build a custom Hugo theme from scratch by hand. I already have so much on my plate, this would never have been even thought of as a possibility. The code is probably not great, and I know that, but I kinda don't care? It's not rocket science, not brain surgery, or software running on a plane keeping things safe. It's just a simple personal website. Without AI it just wouldn't exist at all. I'd still be on the old academic theme, or I'd have spent three months learning Hugo templating and given up halfway through because I have other projects I want to work on more, or found another theme that is kinda what I want, but not quite.

With AI I could finally make something that feels like me, in a way. And it took about a week or two of actual concentrated work, which is wild. I really like this idea of personalisation with the help of AI - "I want this specific thing for my website" - aaaand there you go. I need this specific software for my workflow - done. And so on. Of course, not perfect, but it's a huge step towards that vision of personalisation for everyone, not just those with the time and resources to learn how to make things themselves. I probably will write more about this idea of personalisation with AI in the future, because I think it's really interesting and important.

The theme is open-sourced as well (https://github.com/ioiototm/Multimode-Studio-Hugo-Theme). Although, going back to that point of personalisation, would anybody even want to use it, when they can ask Claude to make something very specific to them? And it already is quite specific to me already... Whether anyone ever will, who knows. But it feels right to give it away. That's kind of the whole point of this site.

