# FAQ Section Implementation

This repository contains the implementation of a responsive and interactive FAQ section,
developed as part of a test assignment for Kryptonum.
The design is based on a [layout provided in Figma](./design.pdf), ensuring precise adherence to the visual specifications.
It emphasizes high-quality code, attention to detail, and adherence to best practices in web development.
Overall, it took about 12–14h to make everything work as expected, since I didn't really work with Astro before.

## 🚀 Features

- Dynamic FAQ Section: Expanding and collapsing FAQ items with smooth animations for both opening and closing.
- Progressive Loading: A "Load More" button dynamically loads additional FAQ items in batches.
- Responsive Design: Fully responsive layout designed to work seamlessly on various devices.
- Accessibility: Built-in support for aria-expanded attributes to enhance accessibility.

## 🛠️ Tech Stack

- Astro: For building a performant static website.
- Vanilla JavaScript: Handles dynamic interactions and animations.
- CSS: Custom styles for the FAQ section and its components.

## ⚙️ How It Works

1. FAQ Item Interaction:
   - Clicking an FAQ item expands or collapses its content.
   - Animations for both actions ensure a smooth user experience.
2. Load More Functionality:
   - Initially, only 10 FAQ items are displayed.
   - Clicking “Load More” dynamically appends the next set of items.

## 🔧 Setup Instructions

### 1. Clone the repository:

```bash
git clone https://github.com/Guliveer/kryptonum-challenge.git
cd kryptonum-challenge
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Run the development server:

```bash
npm run dev
```

### 4. Build for production:

```bash
npm run build
```

## 📝 Notes on the Assignment

The implementation was guided by Kryptonum’s Engineering Wiki and [Figma design](./design.pdf). The process included adhering to their best practices and replicating the provided FAQ design accurately.

This project serves as a demonstration of:

- Code quality.
- Responsiveness and accessibility.
- Timely delivery and attention to detail.

---

Thanks for the opportunity to showcase my skills! 😊
