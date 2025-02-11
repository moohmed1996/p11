from flask import Flask, render_template, url_for

app = Flask(__name__)

# قائمة المنتجات مع الصور
products = [
    {"name": "منتج 1", "price": "10$", "image": "product1.jpg"},
    {"name": "منتج 2", "price": "20$", "image": "product2.jpg"},
    {"name": "منتج 3", "price": "30$", "image": "product3.jpg"},
    {"name": "كوناي انمي وزن 20 غرام شبه حديد ", "السعر": "30الف", "image": "product4.jpg"},
]

@app.route("/")
def home():
    return render_template("index.html", products=products)

if __name__ == "__main__":
    app.run(debug=False)
