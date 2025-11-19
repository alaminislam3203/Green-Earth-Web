# 🌿 Green Earth Website

A fully responsive, interactive **Plant Shop Application** built with modern JavaScript. It includes dynamic category filtering, product listing, modal-based plant details, and a fully functional cart system.

---


🔗 **Live Site:**
[https://alaminislam3203.github.io/Green-Earth-Web/](https://alaminislam3203.github.io/Green-Earth-Web/)


## 🚀 Features

### ✅ **1. Dynamic Categories Loading**

* Fetches plant categories from API.
* Highlights active category.
* Loads plants based on selected category.

### ✅ **2. Plant Listing Section**

* Displays all plants with image, category, price, and description.
* "Add to Cart" button with real-time cart updates.
* Clicking on plant name opens detailed modal.

### ✅ **3. Loader Animation**

* Shows loader while fetching API data.
* Smooth hide/show transition.

### ✅ **4. Plant Detail Modal**

* Detailed plant information (image, price, description).
* Clean UI with `dialog.showModal()`.

### ✅ **5. Shopping Cart System**

* Add items to cart.
* If item already exists, quantity increases.
* Remove items from cart.
* Auto-updates total price.

### ✅ **6. Clean UI / UX**

* TailwindCSS-based styles.
* Fully responsive grid.
* Smooth hover and click animations.

---

## 📁 Folder Structure Example

```
📦 plant-shop-app
 ┣ 📂 assets
 ┣ 📂 scripts
 ┃ ┗ 📜 app.js
 ┣ 📂 styles
 ┃ ┗ 📜 style.css
 ┣ 📜 index.html
 ┣ 📜 README.md
```

---

## 🔗 API Endpoints Used

| Action                 | Endpoint                                                 |
| ---------------------- | -------------------------------------------------------- |
| Get All Categories     | `https://openapi.programming-hero.com/api/categories`    |
| Get All Plants         | `https://openapi.programming-hero.com/api/plants`        |
| Get Plants by Category | `https://openapi.programming-hero.com/api/category/{id}` |
| Get Plant Details      | `https://openapi.programming-hero.com/api/plant/{id}`    |

---

## 🧠 How It Works

### **1. Page Loads**

* Fetches categories.
* Fetches all plants.

### **2. User Interacts**

* Select category → loads filtered plants.
* Click plant → opens modal.
* Add to cart → updates cart list.
* Remove from cart → recalculates total price.

---

## 🛒 Cart System Logic

* Each cart item has:

  ```js
  {
      plantName: "Aloe Vera",
      plantPrice: 350,
      quantity: 1
  }
  ```
* If same item is added again → `quantity + 1`
* Shows total price dynamically.

---

## 📸 UI Preview (Conceptual)

* Sidebar with categories.
* Main cards grid.
* Beautiful modals.
* Sticky cart on right side.

---


---

## 📌 Author

**MD AL-AMIN ISLAM**

Feel free to modify and expand this project! 
