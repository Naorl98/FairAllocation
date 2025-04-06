
# High Multiplicity Fair Allocation Web App

This project implements a **high multiplicity fair allocation** algorithm as a web-based application using Flask. It enables users to manually enter or upload input data and receive an allocation result that is **envy-free** and **Pareto optimal**.

## 🧠 Project Summary

1. **Web-based Allocation Tool**: Built a user-friendly Flask web app to process fair allocation problems from user inputs or CSV files.
2. **Advanced Fairness Algorithm**: Integrated an algorithm based on the AAMAS 2021 paper to ensure results are envy-free and Pareto optimal.
3. **Data Handling & Visualization**: Output presented in downloadable CSV format and rendered clearly in HTML with intuitive design.

## 🛠️ Technologies Used

- **Languages**: Python, HTML, CSS
- **Libraries**:
  - `Flask` (web server)
  - `cvxpy`, `numpy` (optimization and numeric computation)
  - `fairpyx` (custom allocation logic)
- **Tools**: FTP server for deployment, CSV parsing, Jinja2 templating

## 📁 Project Structure

```
├── app.py                      # Flask app entry point
├── routes.py                  # Routing and form handling
├── high_multiplicity_fair_allocation.py  # Core allocation logic
├── templates/
│   ├── index.html             # User input form
│   ├── result.html            # Result rendering
│   └── result_csv.html        # CSV result rendering
├── static/
│   └── style.css              # Custom styles
```

## 🚀 Run Instructions

```bash
pip install -r requirements.txt
python app.py
```

Then go to `http://localhost:2577` in your browser.

## 📄 Source Paper

[High-Multiplicity Fair Allocation Made More Practical](https://www.ifaamas.org/Proceedings/aamas2021/pdfs/p260.pdf)

## 👨‍💻 Authors

- Naor Ladani
- Elor Israeli

---
