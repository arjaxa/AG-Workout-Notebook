# AG-Workout-Notebook
personal AI-powered workout planner that learns your training style and generates custom workout plans

[![Live Demo](https://img.shields.io/badge/Live_Demo-Streamlit-FF4B4B?style=for-the-badge&logo=streamlit)](https://workout-notebook.streamlit.app/)

---

## Key Features

| Feature | Description |
|---------|-------------|
| ** Weekly Planner** | Choose 3, 4, or 5 training days per week – each day is a separate tab. |
| ** Hand‑write Mode** | Build your own workout notebooks with dynamic rows (add/delete exercises). |
| ** AI Auto‑Generate** | Let the AI create a full week of workouts based on your saved training history. |
| ** Smart Regenerate** | Regenerate any single exercise (even inside a superset) – the model learns from your preferences. |
| ** Superset & Tri‑set Support** | Add up to 3 exercises per row, each with independent reps but shared sets. |
| ** Password‑Protected Saving** | Only the owner can add new data – visitors can explore without corrupting the model. |
| ** Real‑Time Learning** | The more you save, the smarter the AI becomes – it learns the exercise sequences, rep ranges, and set volumes. |

---

## How the AI Works

The app uses a **first‑order Markov chain** to learn the patterns in your workouts:

1. **Exercise Transitions** – Tracks which exercises typically follow others (e.g., Bench Press → Incline Press).
2. **Rep Preferences** – Learns your typical rep ranges for each exercise.
3. **Set Preferences** – Learns your typical set volumes for each exercise.

After saving just a few weeks, the AI starts generating plans that feel like *your* style – progressively improving with every new saved workout.

---

## Interface Preview

### Dashboard & Weekly Selection
*Choose your training frequency and dive into the planner.*

<img width="1826" height="780" alt="Screenshot 2026-06-19 110131" src="https://github.com/user-attachments/assets/35c5cf33-275f-4d01-945c-b6dd44dd4b0c" />


### Hand‑write Mode
*Build your own notebook – add rows, create supersets, and adjust reps/sets per exercise.*
<img width="1837" height="833" alt="Screenshot 2026-06-19 111306" src="https://github.com/user-attachments/assets/fa4e9ba1-7295-44a4-934b-a29b35406de0" />



### AI Auto‑Generate
*Let the AI generate a complete week based on your saved history.*

...

### Superset & Regenerate
*Add up to 3 exercises per row and regenerate individual moves.*
<img width="1836" height="837" alt="Screenshot 2026-06-19 111357" src="https://github.com/user-attachments/assets/3359b1f9-2d86-4fa0-8d4a-96d51a2b1c70" />



### Admin Panel
*Add custom exercises with new muscle groups via the sidebar.*

<img width="363" height="782" alt="Screenshot 2026-06-19 111500" src="https://github.com/user-attachments/assets/8ea0af27-7e44-49cb-9bc4-4fa322e421be" />


---

## Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend + Backend | Python + Streamlit |
| Database | SQLite (local) |
| AI Model | Markov Chain + Frequency Tables |
| Authentication | Password‑Protected Saving |
| Styling | Streamlit Custom CSS |

---

## Example Use Cases

| Scenario | How the app helps |
|----------|-------------------|
|  **Lifting 5x/week** | Plan Push/Pull/Legs/Upper/Lower with personalized exercise order. |
|  **Time‑constrained days** | Use auto‑generate to get a quality plan in seconds. |
|  **Changing split** | Switch from 4‑day to 3‑day – the AI adapts to your preferred exercise order. |
|  **Superset experimentation** | Build supersets, save them, and the AI learns your pairings. |

---


## License

This project is for **personal use only**. The source code is private.

