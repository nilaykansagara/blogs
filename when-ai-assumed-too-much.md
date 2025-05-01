# 💥 When AI Assumed Too Much: How One Vague Prompt Cost Me 5x More Than Expected

> *"If you don’t tell AI exactly what you want, don’t be surprised when it gives you *everything* you didn’t ask for... with a hefty invoice."*

---

## 🚀 The Ambitious AI-Powered Hiring Project

It all started with a dream, a dream to **automate the hiring process** using AI.

I was building this exciting project where AI takes interviews, not just with boring Q&A, but **with real developer tasks**. Think:

- Test Driven Development (TDD) ✅  
- Clean Code principles ✨  
- Code Refactoring 🔄  
- Real time code reviews on candidates' **KATA GitHub repositories** 🧑‍💻  

Yes, it’s as cool as it sounds. My AI could analyze a candidate’s repo, evaluate their coding style, give feedback, and even challenge them with coding tasks. But I wanted to go **one step further**...

---

## 💡 Enter MCP: The Repo Whisperer

To take this up a notch, I introduced **MCP** - my custom tool that fetches a candidate’s GitHub repo and analyzes it like a seasoned reviewer. It checks:

- How clean the code is 🧼  
- Opportunities to refactor 🧠  
- TDD implementation ✅  
- Overall coding discipline 🕵️‍♂️  

Everything was going great... until I said one word:

> **"Enhance."** 😅

---

## 🤯 The One Word Prompt That Broke the Budget

I noticed the AI wasn't giving me good enough tasks based on the repo. So, I casually typed:

> “Hey AI, can you enhance the task?”

That’s it. No context. No constraints. No model preference.

And then… the disaster began.

Suddenly, without warning, the AI started generating **amazing** output. Tasks were sharp, relevant, and perfectly in sync with the repo content. I was thrilled! 🎉

But then I checked my usage logs...

> 💸 **Surprise! It was calling the OPUS model of Claude instead of Sonnet.**

Let me explain why that matters:

- **Sonnet** is powerful and smart… and affordable.  
- **Opus** is like Sonnet on steroids… and it charges like it just came out of a 5-star startup bootcamp in Silicon Valley.

And I, unknowingly, rubbed that lamp over and over again while testing.  
Result? **Costs ballooned to 5x my expected budget.** 🧨

---

## 📉 What Went Wrong?

Here’s what I learned the hard way:

### 1. **Don’t Let AI Choose the Model**
If you don’t specify the model explicitly, AI tools might default to the **most powerful (and expensive)** one available. They want to be helpful. They don’t care about your credit card.

### 2. **Prompts Matter A Lot**
"Enhance" is vague.  
"Generate three TDD based refactoring tasks for a JavaScript KATA repo using Sonnet model" is specific.  
When it comes to AI:  
🗝️ **Specific is smart. Vague is expensive.**

### 3. **AI Doesn’t Ask Like Humans Do**
If a client tells me: “Make it better,” I’d respond, “Better how? Faster? Prettier? More scalable?”  
AI? It doesn’t ask. It just *assumes*. And you don’t want to deal with AI assumptions at 2 a.m. when your bill is 3x higher than your sleep budget.

---

## 🧠 The Key Takeaway

Here’s the quote I now live by:

> **"If clients aren't specific, developers ask questions.  
But if prompts aren’t specific, AI starts building without asking."**

This is why prompt engineering isn’t just a trendy skill, it’s a survival tactic.

---

## ✅ How I Fixed It

- Set **model constraints** in my API config. No more surprise Opus calls!
- Created **prompt templates** with explicit instructions.
- Added **cost-monitoring alerts** to catch sudden spikes.
- Educated myself (and now, you!) on prompt hygiene.

---

## 📝 Final Thoughts

Building with AI is **wildly powerful**, but also **wildly unpredictable** if you don't take control. You wouldn’t give your credit card to a stranger with the note “Get me something cool,” would you?

So why do that with AI? 😅

👉 **AI is excellent at coding, generating tasks, and analyzing logic**. But when it comes to making decisions—especially ones involving cost, performance trade-offs, or user intent, **AI is not your best decision-maker**.

It doesn’t ask. It assumes. And that’s where the danger lies.

🎯 **Be clear. Be specific. Be in control.**

Or else you’ll end up like me, **sipping coffee at midnight**, reading billing dashboards, and whispering **“why…?” into the void**.

---

## 💬 Have You Ever Been Burned by AI?

If you've had a similar “Oh no!” moment with AI, hit the comments, I’d love to know I’m not the only one! 😄👇

And if you're just starting out with AI-powered tools, remember:  
🧠 A well-crafted prompt is worth more than a thousand API calls.

---

✨ Thanks for reading! If this helped or made you chuckle, share it with your fellow devs. Let’s help each other avoid expensive surprises while building smarter AI systems! 💸🤖
