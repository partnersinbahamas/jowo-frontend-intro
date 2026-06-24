# 🔵 CSS Task 1 — Page layout

### 🎯 Goal

Style the basic page layout (header, main, footer).

### 📦 Requirements

- Create a file called `app.css`
- Conntect your `app.css` file to`app.html` using `<link>` tag.

#### 🌍 Global styles

- Remove default page margin
- Set a light gray `#f2f2f2` background color for the page
- Set a global font `"Gill Sans", sans-serif`

---

#### 📐 Layout

- Place `header` at the top of the page
- Place `footer` at the bottom of the page
- `main` should take all available space between header and footer

---

#### 🧭 Header & Footer

- Set a fixed height `40px`
- Add white background `#fff`
- Center text horizontally and vertically

---

#### 📦 Main section

- Center content horizontally and vertically inside `main`
- There should be space between elements inside (form and profile card)

---

### 💡 Hints

- You can style elements directly using tags:
  ```css
  body {}
  header {}
  main {}
  footer {}
  ```

  You do not need to use `.class` for this task.

- Try using `flexbox` for layout
- You may need:

  - `display: flex`
  - `flex-direction`
  - `align-items`
  - `justify-content`

---

### 👀 Check yourself

- Is there any scroll on the page? (there shouldn’t be)
- Is header visible at the top?
- Is footer visible at the bottom?
- Is content centered in the middle?
- Is there space between elements inside `main`?

---

### ✅ Expected result

![Expected result](../../assets/task-results/css/task-1-result.png)

