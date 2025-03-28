# 📦 E-Commerce Product Scraper

## 🔍 About the Project
This Python-based web scraper fetches product details (title, price, image, and link) from **Flipkart** and **Amazon** based on your search query. It extracts relevant product information and displays it in a structured format.

## 🚀 Features
- 🔹 **Scrapes Flipkart & Amazon** for product details
- 🔹 Extracts **title, price, image, and link**
- 🔹 **User-friendly** command-line interface
- 🔹 **Error handling & logging** for a smooth experience

---

## 🛠 Installation & Setup
Follow these steps to set up and run the scraper on your system:

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/Ecommerce-Scraper.git
cd Ecommerce-Scraper
```

### 2️⃣ Create a Virtual Environment
```sh
python -m venv env
source env/bin/activate  # For macOS & Linux
env\Scripts\activate    # For Windows
```

### 3️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

---

## 🏃 Usage
Run the script and enter the product name:
```sh
python ecommerce_scraper.py
```
Then, enter the product name (e.g., **Redmi Note 9**) to fetch its details from Flipkart and Amazon.

Example Output:
```sh
Flipkart Product Details:
Title: Redmi Note 9 (4GB RAM, 64GB Storage)
Price: ₹11,999
Link: https://www.flipkart.com/product-link
Image: https://image-url

Amazon Product Details:
Title: Redmi Note 9 (4GB RAM, 64GB Storage)
Price: ₹11,990
Link: https://www.amazon.in/product-link
Image: https://image-url
```

---

## 📦 Dependencies
Ensure you have the following installed (automatically installed via `requirements.txt`):
```
requests
beautifulsoup4
logging
```

---

## 📝 License
This project is **open-source** and available under the [MIT License](LICENSE).

## 👨‍💻 Author
Developed with ❤️ by **Nitish**

💬 Feel free to connect on [GitHub](https://github.com/your-username)!

