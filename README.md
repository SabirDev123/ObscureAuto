# 🚗 ObscureAuto

> Discover obscure, forgotten, and fascinating automobiles, one random pick at a time.

ObscureAuto is a lightweight Python-based car database that displays random obscure vehicles from around the world.

From forgotten production cars to unusual concepts, prototypes, race cars, and one-offs, ObscureAuto is a small digital collection of automotive oddities.

---

## ✨ Features

- 🚗 Random obscure car discovery
- 📄 JSON-based car database
- 🐍 Written in Python
- ⚡ No external dependencies
- 🎲 Random car selection
- 🔁 Prevents immediate duplicate cars
- 📚 Displays detailed vehicle information:
  - Name
  - Manufacturer
  - Country
  - Year
  - Category
  - Obscurity rating
  - Description

---

## 🎮 Controls

| Key | Action |
|---|---|
| Enter / Return | Show another random car |
| Q | Quit |
| X | Quit |

---

## 📂 Project Structure

```
ObscureAuto/
│
├── main.py        # Main Python program
├── cars.json      # Car database
├── README.md      # Documentation
├── LICENSE        # License file
└── .gitignore     # Ignored files
```

---

## 🚀 Running ObscureAuto

### Requirements

- Python 3.x

No additional libraries are required.

### Run

Clone the repository:

```bash
git clone https://github.com/SabirDev123/ObscureAuto.git
```

Enter the project folder:

```bash
cd ObscureAuto
```

Run the program:

```bash
python3 main.py
```

---

## 🗃️ Database Format

Cars are stored inside `cars.json` as objects.

Example:

```json
{
  "id": "toyota_will_vi",
  "name": "Toyota WiLL Vi",
  "manufacturer": "Toyota",
  "country": "Japan",
  "year": 2000,
  "category": "Production Car",
  "obscurity": 8,
  "description": "A retro-inspired sedan created for Toyota's WiLL project."
}
```

Adding a new car is simple:
1. Open `cars.json`
2. Add another object
3. Save the file
4. Run ObscureAuto again

---

## 🚗 Example Cars

Some cars featured in the database:

- Toyota WiLL Vi
- Toyota Caldina GT-Four
- Toyota GT-One
- Toyota Mega Cruiser
- Toyota Origin
- Dechamps Tonneau
- De Dion-Bouton Type ADL
- McLaren X1
- Bugatti 18.4 Veyron
- Autozam AZ-1
- Mitsuoka Orochi
- Nissan Figaro
- Nissan S-Cargo
- Vector W8
- Cizeta V16T
- Panther 6
- Covini C6W
- Stout Scarab
- Citroën Karin
- Volkswagen XL1

…and many more unusual automotive machines.

---

## 🎯 Goal

The goal of ObscureAuto is simple:

> Make discovering forgotten cars fun.

No massive database.
No complicated setup.
Just interesting cars.

Every vehicle has a story.

---

## 🌱 Future Ideas

Possible future improvements:

- 🖼️ Add vehicle images
- 🔎 Search system
- 🌍 Filter by country
- 🏭 Filter by manufacturer
- ⭐ Favorite cars
- 📊 More specifications
- 🏁 Add racing cars and prototypes
- 📚 Expand the database

---

## 🤝 Contributing

Want to add an obscure car?

1. Fork the repository
2. Add the vehicle to `cars.json`
3. Make sure the information is accurate
4. Submit a pull request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👤 Author

Created by **SabirDev123**

Built with:

- 🐍 Python
- 📄 JSON
- 🚗 Automotive curiosity

---

## 🚗 Philosophy

ObscureAuto is not about having the biggest car database.

It's about finding the cars that history forgot.

A strange prototype.
A forgotten production model.
A legendary machine hiding in automotive history.

Every car deserves to be remembered.

---
