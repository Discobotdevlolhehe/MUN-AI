# Vistatia  
Made entirely with **coffee, 3AM breakdowns**, and emotional damage from my ex.  
- If you understand what half of this code does.. please touch some grass, or maybe a girl [if you can you compsci major] -- or whatever gets you to leave that  blue-light-emitting screen.  
---

## 💩 What *is* this?

I’ve seen way too many newcomers freeze, flop, or full-on **panic shit** during a GSL. And let’s be real — MUN chairs are less forgiving than my ex during a text fight.

So I made **Vistatia** [formerly mun ai]:  
Your very own (reluctantly helpful) MUN assistant to stop you from becoming public speaking roadkill. Whether it’s **general, crisis, or some hybrid hellspawn**, this thing’s got you *kinda* covered.

---

## 🚀 Features (because you’re greedy and helpless)

Yeah, you’re peeking here before you’ve even tried the site. I get it. Here’s what you’re getting — **barely deserved** but still better than your last relationship:

### 1. 🧾 Directive AI  
Punch in what you want, get a directive **better than whatever ChatGPT mumbles out with its ehtical bullshit**. Yes, it's spicy [spicier than the tea any female will ever give you].

### 2. 🧠 Assessment AI  
Wanna know how **cooked** your next move is? Feed it your "strategy" (lmfao), and it’ll tell you if you're **Michelin-starred** or just *burnt toast*.

### 3. 🗺️ Strategy AI  
Lost faith in yourself? Good. This AI will hand-hold you through actual strategies [unlike someone you used to know], assuming you have a goal that isn't just "survive the committee." or any such bs.

### 4. 📢 Speech AI  
Time to step out of your shy little corner and **speak up**. Drop in a clean, clear prompt (unlike your messy love life), and it’ll draft a speech you *might* not butcher.

### 5. 💥 POI / POO / R2R AI  
Because **arguing is the entire point**. Heard someone say dumb shit? Throw in a summary and get an *intellectual missile* back. Use responsibly. Or don’t.

### 6. 🔥 Rebuttal AI  
When someone actually dares to attack you (emotionally, verbally, or via moderated caucus), this AI claps back — hard.  
> Warning: Time-limited? So is your patience.

### 7. 📚 Guide AI  
Your background guide looks like it was printed on toilet paper. Give this AI your agenda, committee type, freeze date, and maybe a human soul — and you’ll get something readable.  
> Requires 12 functioning brain cells. You’ve been warned.

---

## 🧪 How to use this cursed masterpiece

*sips coffee* Alright, here we go...

1. **ID field:** Type *literally anything*. It’s there for ✨vibes✨.  
2. **Dropdown menu:** Pick what you want to do.  
   *(yes, you're really about to let an AI do your job)*  
3. **Prompt field:**  
   Write a prompt.  
   - NOT your breakup letter  
   - NOT a vague “help me pls”  
   - Be **clear, detailed, specific** — like you should've been with your ex.  
4. **Click "Generate" or press ALT + Enter.**  
   That’s it. Your fate is sealed.

---

## ❌ What this *won’t* do

Not covering that. If you find out the hard way, that’s a **skill issue.**. Not my problem

---

## 🔧 Wanna install it locally? You frickin masochist.

If you’re really that desperate like your situationship? then:

### Tech Stack:
- React.js
- Node.js

### Procedure:

1. Download or clone it  
2. Open the backend Folder  
3. Get **~6 Mistral API keys** (use small model — they’re free).  
   [Get them here](https://console.mistral.ai)  
   - you will need those many to avoid overloading the api [like your ex to you] and to multitask *'efficiently'*  [if this term is in your dictionary]
4. In the `AI` folder, every subfolder has a dedicated `index.js` <br>[**DO NOT** touch `shared_memory.json` or `system_prompt.txt` this is not your girlfriend who pretends that you're the biggest she's ever had]  <br>
On `line 5` find this: <br>
`const API_KEY = "placeholder";` 

Replace `placeholder` with your api key just like how your gf replaces you on a good saturday night.  
Repeat it for every `index.js`

5. run `cd backend` then `npm start` in the backend side  
6. run `cd ..`  
7. run `cd frontend` then `npm run dev` on the frontend side  
- or just open two seperate consoles [sorry I don't speak in mac or linux]

---

#### Side note:

This was meant strictly for **local deployments** — that’s why I didn’t bother making a dedicated `.env` file.  
Just like your father who didn’t bother coming back with the milk he left for 15 years ago.

If you wanna be fancy and set one up for public deployment? Go ahead. I won’t stop you.  
But maybe the license will 😉 jkjk (or maybe... 👀)

Also, don’t come chasing me for slapping this onto a Vercel app.  
**Yes, it exists — so you know what you’re getting.**  
**No, it’s not for commercial use like your ex.**  
If it crashes? Just know Vercel decided to be a bitch and start playing hard to get.

Pull requests, suggestions, critiques, feedback? Absolutely.  
**But don’t come for my tone. That will forever be Non-Negotiable.**


---

### 🗨️ Dev's Note  
- ⚠️ Most MUN's don’t even let you use phones [unless its a urgent call or smth], let alone AI tools or the internet. This is a preparation weapon, not your secret in-committee cheat device. But if you *do* sneak it in, Be my guest, I'm not the one to blame, I warned ya

Please, for the love of all committees, don’t fully rely on this. It won’t save your ass in Press Conferences, moderated hellfires, or if someone drops a historical crisis in your lap, or the worst one... The executive board.

This tool is a crutch, not a replacement for research. Learn your basics. But hey — I’m not your supervisor.

Enjoy your 1st, 2nd, or 15th breakdown at a Model UN.

Peace out,

— your caffeine-fueled developer,  
running on regret, Red Bull, and a 3AM Monday meltdown and zero survival instincts 💀

---
