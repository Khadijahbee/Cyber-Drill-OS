[README.md](https://github.com/user-attachments/files/34860095/README.md)
# CyberDrill: 60-Second Incident Trainer

**Decide in 60 seconds. Learn to respond to real cyber attacks.**

CyberDrill is a gamified cyber incident-response simulator. You face a realistic attack (phishing, ransomware, brute force and more), choose a response before a 60-second timer runs out, and get instant feedback on whether your decision was right and why.

**Live demo:** https://cyber-trainee.bonto.page/

---

## The problem

Most cybersecurity training is slides and textbooks. When a real incident happens, people freeze. CyberDrill lets people practise those split-second decisions safely.

## How it works

1. **Pick a learning mode:** Beginner / Student, Employee awareness, or SOC analyst.
2. **Read the alert** on the SOC-style dashboard (severity, source, asset, live log feed).
3. **Choose a response** from four options before the 60-second timer hits zero.
4. **Get feedback:** the system scores your choice and explains why each option was right or risky.
5. **Earn points, build a streak, rank up,** then try another incident.

## Who it is for

| Audience | What they practise |
| --- | --- |
| Students and beginners | Spotting common threats like phishing |
| Employees | Everyday security awareness |
| SOC analysts | Triage and containment decisions under pressure |

## Features

- 60-second decision timer with a block progress bar and a warning phase
- Three learning modes with different incident sets
- Realistic incidents: phishing, MFA fatigue, rogue USB, ransomware, SSH brute force, CEO wire fraud, data exfiltration
- Scoring: response points plus a speed bonus (up to 25), minus a hint penalty
- Ranks, streaks and a saved high score
- Retro CRT arcade interface with sound effects and keyboard controls

## Scoring

| Part | Points |
| --- | --- |
| Best response | 100 |
| Partly correct response | 10 to 60 |
| Speed bonus (good answers only) | up to 25 |
| Hint used | -10 |

## Controls

| Key | Action |
| --- | --- |
| `Enter` | Start simulation |
| `1` to `3` | Choose a learning mode |
| `1` to `4` | Choose a response |
| `H` | Use a hint |

## Tech stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js
- **Hosting:** https://cyber-trainee.bonto.page/

## Project structure

```
.
├── public/        # Frontend (HTML, CSS, JS)
├── data/          # Incident data
├── lib/           # Backend helper code
├── test/          # Tests
├── app.js         # App setup
├── server.js      # Server entry point
├── setup.js       # Project setup
└── package.json
```

## Run locally

```bash
git clone https://github.com/Khadijahbee/Cyber-Drill-OS.git
cd Cyber-Drill-OS
npm install
npm start
```

Then open https://cyber-trainee.bonto.page/ in your browser.

## Team

Built during a hackathon by **Ctrl Freaks**.

| Name | Role | GitHub |
| --- | --- | --- |
| Khadijah Shafiq | Frontend and UI design | [@Khadijahbee](https://github.com/Khadijahbee) |
| Malaika Asim | Backend | [@Alpha2634](https://github.com/Alpha2634) |
| Afreen Fiaz | Pitcher | [@afreenfiaz](https://github.com/afreenfiaz) |

## License

MIT License. See the [LICENSE](LICENSE) file.
