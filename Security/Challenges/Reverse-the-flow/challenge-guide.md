# Reverse the Flow: Participant Guide

Cybersecurity Subsection, MicroClub

This time, **you** are the ones creating the challenges! This guide explains what to do, what to submit, and what happens next.

---

## 1. What Is It?

Create a small cybersecurity challenge for other members to solve. After a review by the IT Core Team, it gets published, and everyone can try to solve it.

You learn more by building a challenge than by solving one: to design a vulnerability or a puzzle, you have to understand it deeply.

## 2. Who Can Join?

- Every member, **no matter your level**.
- **Alone or in a small team** (your choice).
- One challenge per participant or team.

## 3. What to Create

Pick any category you like:

- Web
- Pwn
- Crypto
- Forensics
- Network
- Reverse engineering
- Other 

Choose a difficulty: **easy, medium, or hard**.

## 4. What to Submit

Your submission must include:

| Item | Description |
| --- | --- |
| **Title** | Short and clear |
| **Category and difficulty** | See section 3 |
| **Story example** | A short scenario that sets the scene for players |
| **Explanation** | What the challenge is about and which **vulnerability or concept** it covers |
| **Files or environment** | The files, or a Docker/VM setup if needed (with instructions to run it) |
| **Flag** | The exact flag and its format |
| **Hints** | One or two, optional |
| **Solution (writeup)** | Step-by-step solution |

## 5. Rules

- **Original work:** create your own challenge. If you are inspired by something, credit your sources.
- **Safe environments only:** your challenge must run in an isolated lab (Docker or VM). Never target real systems, real websites, or real people.
- **No personal data:** do not use real passwords, real emails, or private information.
- **No harmful code:** nothing that could damage a player's computer.
- **It must be solvable:** the flag must be reachable, and your writeup must prove it.
- **Be respectful:** keep the content appropriate for everyone.

## 6. How It Works

1. **Create** your challenge and prepare your submission.
2. **Submit** it before the deadline.
3. **Review:** the IT Core Team tests it and may ask for fixes.
4. **Publish:** your challenge is released, and everyone can try to solve it.

## 7. How to Submit

You submit through a **Pull Request** on our GitHub repository: [repo link]

1. **Fork** the repository to your own GitHub account.
2. **Clone** your fork and create a new branch named after your challenge, for example `challenge/my-challenge-name`.
3. **Create a folder** for your challenge inside `Security/Challenges/Reverse-the-flow/`, and add:
   - `README.md`: title, category, difficulty, story example, and explanation
   - the challenge files, or a Docker/VM setup with instructions to run it
   - an optional `hints.md`
   - Writeup `writeup.md`
4. **Commit and push** your branch to your fork.
5. **Open a Pull Request** targeting the `Security` branch and fill in the PR template.


## 8. What We Check

- Does the challenge work, and can it be solved?
- Is the **story** clear and the **explanation** accurate?
- Is the difficulty fair?
- Is the environment safe and easy to run?
- Is the writeup complete?

## 9. Need Help?

Not sure what to build, or stuck on a technical detail? Ask us in the server or by DM. We're happy to help you choose an idea, and no question is too basic. 

Good luck, and have fun! ^-^
