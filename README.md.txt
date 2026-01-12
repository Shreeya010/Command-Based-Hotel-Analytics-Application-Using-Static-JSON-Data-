# Hotel Analytics System

## How to Run

1. Clone this repository or download the ZIP file and extract it.
2. Install required Python packages using:
	
	pip install -r requirements.txt

3. Run the main program:
	
	python main.py

4. Follow the on-screen instructions to interact with the system.

---

## Supported Commands

| Command                | Description                                  |
|------------------------|----------------------------------------------|
| today's sale           | Shows today’s total sales                    |
| payment wise sale      | Shows sales categorized by payment type     |
| cancelled bills        | Displays cancelled bills                     |
| cancellation_risk   | Predicts the probability of a bill being cancelled |
| exit                   | Exit the application                         |

---

## ML Logic

- **Model:** Currently a simple placeholder function (`ml_model.py`) for demonstration.
- **Input Features:** amount, payment method, room type, cancellation
- **Output:** Probability of cancellation (0 to 1).
- **Prediction:** The `cancellation_risk` command uses the ML logic to give a cancellation probability for a sample input.  




