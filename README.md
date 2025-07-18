 🛒 Amazon Clone using Flask

An Amazon-style eCommerce website built using **Flask** (Python Web Framework). This project replicates the core features of Amazon including user authentication, product listing, shopping cart, and order checkout.

---

## 🚀 Features

- ✅ User Signup, Login, Logout (Session-based auth)
- 🛍️ Browse products by categories
- 🛒 Add to Cart / Remove from Cart
- 💳 Checkout system (Cash on Delivery / Dummy Payment)
- 🔍 Search products by name or keyword
- 🖼️ Admin panel to manage products (optional)
- 📦 Order history tracking

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap, Jinja2
- **Backend:** Flask, Python
- **Database:** SQLite / MySQL (choose one)
- **Authentication:** Flask-Login / Session

---

## 🧰 Requirements

- Python 3.7+
- Flask
- Flask-Login
- Flask-SQLAlchemy
- Jinja2

Install dependencies:

```bash
pip install -r requirements.txt
📁 Project Structure
php
Copy
Edit
amazon-clone/
│
├── static/               # CSS, JS, images
├── templates/            # HTML templates
│   ├── index.html
│   ├── product.html
│   └── ...
├── app.py                # Main Flask app
├── models.py             # DB models
├── routes.py             # All Flask routes
├── forms.py              # Flask-WTF forms (optional)
├── requirements.txt
└── README.md
⚙️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/navyanigam/amazon-clone-flask.git
cd amazon-clone-flask
Set up a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app:

bash
Copy
Edit
python app.py
Open your browser and visit:
http://127.0.0.1:5000/

📸 Screenshots
(Add images or links to demo GIFs here)

🧪 Optional Enhancements
✅ Add product reviews & ratings

🔒 JWT-based authentication

🛠️ Dockerize the project

🧾 Add Stripe or Razorpay for real payments

📱 Make the site responsive/mobile-friendly

📄 License
This project is licensed under the MIT License.

🙋‍♀️ Author
Your Name - navya nigam

vbnet
Copy
Edit
                                                                                                                                                       
