<<<<<<< HEAD
# AI Week 1b: Git and GitHub Practice :)
=======
# AI Week 1b: Git and GitHub Practice :D asds
>>>>>>> conflict-practice

**Quest International University** · Artificial Intelligence (BCS2044 / BCS2143 / BME4123)
Lecturer: Assoc. Prof. Ir. Ts. Dr. Mah Siew Kien

Welcome! This repository is for practising the GitHub workflow from the Week 1b lab.
There is **no code to write**. You will only edit this README file in your own fork.

---

## What to do (Tutorial Task 4)

Work with a partner. Each of you does every step on your **own fork**, then you swap roles as reviewer.

1. **Fork** this repository to your own GitHub account using the **Fork** button at the top right.
2. **Clone your fork** with VS Code (`Ctrl+Shift+P` › Git: Clone) or GitHub Desktop (File › Clone repository).
3. **Add your partner as a collaborator** on your fork: Settings › Collaborators › Add people. Your partner accepts the invitation.
4. **Create a branch** named `add-about-me`.
5. **Copy the template below** to the end of this README and fill it in. Save, commit with a clear message, and publish the branch.
6. **Open a pull request** from `add-about-me` into `main` **of your own fork**. In the description, say what you changed and why. Request your partner as reviewer.
7. Your partner leaves **one comment on a line** and **requests one change**, such as fixing a typo or adding a detail. Make the change and push again.
8. Your partner **approves**. **Merge** the pull request and **delete the branch**.

> ⚠️ **Important when opening the pull request.** GitHub may suggest sending it to
> `siewkienmah/ai-week1b-git-practice`. Change the **base repository** to **your own fork**,
> so the pull request goes from `add-about-me` into `main` of your fork.
> Do not open pull requests to this original repository.

### Terminal version (optional)

```bash
git clone https://github.com/YOUR-USERNAME/ai-week1b-git-practice.git
cd ai-week1b-git-practice
git switch -c add-about-me
# edit README.md, then:
git add README.md
git commit -m "Add About me section"
git push -u origin add-about-me
```

---

## Template to copy

```markdown
## About me

- **Name:**
- **Programme:**
- **One AI topic I am curious about:**
- **Why it interests me (one sentence):**
```

---

## Rules

- Keep your About me section friendly and professional.
- **Never** put passwords, API keys, phone numbers or your IC number in a repository.
- Ask your lecturer or a classmate if you get stuck. Helping each other is encouraged.

## Submit

Put the link to your **merged pull request** in your Week 1b tutorial file and submit it on
[eQIU](https://eqiu.qiu.edu.my/course/view.php?id=7852).

## About me

- **Name:LIM SHAO QIAN**
- **Programme:Bachelor of Computer Science**
- **One AI topic I am curious about: Agentic AI and autonomous systems**
- **Why it interests me (one sentence): Unlike traditional chatbots that simply generate text responses, AI agents can independently interact with tools, execute code, and carry out multi-step real-world tasks on a user's behalf.**
