# 🤖 fake it till you make it (github edition)

so my github graph looked like a graveyard 💀
and instead of fixing my habits... i fixed the graph

---

## 😏 what this does

this repo uses github actions to:

* make random commits
* multiple times a day
* with realistic messages
* like a totally normal human developer™

basically → it **keeps your graph green** without you doing anything

---

## 🧠 how it works (very simple)

every few hours:

1. github runs a workflow
2. it edits a file (`log.txt`)
3. makes a few commits
4. pushes them

done. graph go 📈

---

## 🎲 why it looks real

* random number of commits (not fixed)
* different commit messages
* runs at "human" hours (evening/night)
* not perfectly consistent

👉 so it doesn’t scream *“this is a bot”*

---

## 💸 cost

free.

like actually free.

github gives:

* 2000 free minutes/month

this uses:

* ~20 mins/month

so yeah… basically nothing

---

## ⚙️ setup (if you wanna copy this)

1. create a repo
2. add:

   ```
   .github/workflows/daily.yml
   ```
3. paste the workflow
4. enable actions
5. run once

and you're done.

---

## 📈 result

your graph goes from:

💀💀💀💀💀
to
🟩🟩🟩🟩🟩

instant glow up

---

## ⚠️ disclaimer

this doesn’t make you a better developer

just a better *looking* one 😭

---

## 🧠 why i made this

* curiosity
* automation practice
* and honestly… the green squares look nice

---

## ⭐ if you liked this

drop a star
or don’t, i’ll commit anyway 😏
