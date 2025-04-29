# 🚚 Shipment Management Form

A web-based **Shipment Management Form** that interacts with the **JsonPowerDB** database. The form captures shipment information and stores it in the `SHIPMENT-TABLE` relation of the `DELIVERY-DB` database. Designed as a mini-project to demonstrate CRUD operations using JPDB APIs.

---

## 📋 Table of Contents

- [Project Description](#project-description)
- [Scope of Functionalities](#scope-of-functionalities)
- [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Examples of Use](#examples-of-use)
- [Illustrations](#illustrations)
- [Project Status](#project-status)
- [Release History](#release-history)
- [Sources](#sources)
- [Other Information](#other-information)

---

## 📌 Project Description

The **Shipment Management Form** is a single-page web app (SPA) built using HTML, Bootstrap, jQuery, and JavaScript. It allows users to:

- Add new shipment records.
- Retrieve shipment details using a unique Shipment Number.
- Update existing shipment details.
- Reset the form to its initial state.

All actions are backed by **JsonPowerDB** — a fast, lightweight, and easy-to-use JSON-based database.

---

## ✅ Scope of Functionalities

- Input Fields:
  - `Shipment No.` *(Primary Key)*
  - `Description`
  - `Source`
  - `Destination`
  - `Shipping Date`
  - `Expected Delivery Date`

- Functional Buttons:
  - **Save**: Saves new shipment data.
  - **Update**: Updates existing shipment records.
  - **Reset**: Clears the form and resets states.

- Validations:
  - No field can be left empty.
  - Primary key check for insertion/update.

---

## 🌟 Benefits of using JsonPowerDB

- **Lightweight and Fast**: Perfect for frontend developers needing minimal backend.
- **Inbuilt API Support**: Directly accessible via AJAX (no additional backend required).
- **Schemaless**: Flexible document structure.
- **Easy CRUD**: Simplified commands like `PUT`, `GET_BY_KEY`, `UPDATE`, `REMOVE`.
- **Secure**: Token-based authentication.

---

## 💡 Examples of Use

- Logistics companies can manage shipment records in a lightweight web app.
- Educational demos for learning CRUD operations with NoSQL-like databases.
- Form-based data collection apps without complex backend.

---

## 🖼️ Illustrations

![Form Screenshot](link-to-your-screenshot-if-applicable)

---

## 📦 Project Status

✅ **Completed** — Functional Save, Update, and Reset buttons integrated with JsonPowerDB using proper validations.

---

## 🧾 Release History

- **v1.0** - Initial release with full CRUD operations.
- **v1.1 (Optional)** - Add date pickers, better validations, and styling (planned).

---

## 📚 Sources

- [JsonPowerDB Docs](https://login2explore.com/jpdb/docs.html)
- [Bootstrap Framework](https://getbootstrap.com/)
- [jQuery Library](https://jquery.com/)

---

## ℹ️ Other Information

This project is part of a **Mini Project Assignment**:
> *“Create a Shipment Management Form to store data in SHIPMENT-TABLE relation of DELIVERY-DB database using JsonPowerDB.”*

---

## 🙋 Author

**Venkatapavan** — Java Full Stack Developer (Fresher)  
Currently an Intern at Revature


