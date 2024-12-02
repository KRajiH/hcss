### **Custom CSS Library Documentation: Width Utility Classes**
#### use cdn
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/KRajiH/hcss@main/hcss%40V1.0.0.css">
```
Our custom CSS library provides easy-to-use utility classes for managing the width of elements. These classes allow you to set widths in **pixels (px)**, **viewport width (vw)**, and **percentages (%)**.

---

#### **1. Width in Pixels (px)**

To define the width in pixels, use the `w-size` class format followed by a number between **1 and 200**.  
- **Class Format**: `w-<number>`  
- **Usage**:  
  - `w-1` => 1px  
  - `w-2` => 2px  
  - `w-3` => 3px  
  - ...  
  - `w-200` => 200px  

**Example**:  
```html
<div class="w-100">This div has a width of 100px.</div>
```

---

#### **2. Width in Viewport Width (vw)**

To define the width in viewport width units, use the `w-vw-size` class format followed by a number between **1 and 100**.  
- **Class Format**: `w-vw-<number>`  
- **Usage**:  
  - `w-vw-1` => 1vw  
  - `w-vw-2` => 2vw  
  - `w-vw-3` => 3vw  
  - ...  
  - `w-vw-100` => 100vw  

**Example**:  
```html
<div class="w-vw-50">This div has a width of 50vw.</div>
```

---

#### **3. Width in Percentages (%)**

To define the width in percentages, use the `w-p-size` class format followed by a number between **1 and 100**.  
- **Class Format**: `w-p-<number>`  
- **Usage**:  
  - `w-p-1` => 1%  
  - `w-p-2` => 2%  
  - `w-p-3` => 3%  
  - ...  
  - `w-p-100` => 100%  

**Example**:  
```html
<div class="w-p-75">This div has a width of 75%.</div>
```

---

### **Summary Table**

| **Measurement** | **Class Prefix** | **Range**  | **Example**         |
|------------------|------------------|------------|---------------------|
| **Pixels (px)**  | `w-`            | 1 - 200    | `w-50` => 50px     |
| **Viewport (vw)**| `w-vw-`         | 1 - 100    | `w-vw-20` => 20vw  |
| **Percentage (%)**| `w-p-`         | 1 - 100    | `w-p-90` => 90%    |

Use these utility classes to simplify and standardize your responsive designs.


### **Custom CSS Library Documentation: Height Utility Classes**

Our custom CSS library includes utility classes for setting the height of elements. These classes support height definitions in **pixels (px)**, **viewport height (vh)**, and **percentages (%)**.

---

#### **1. Height in Pixels (px)**

To set height in pixels, use the `h-size` class format followed by a number between **1 and 200**.  
- **Class Format**: `h-<number>`  
- **Usage**:  
  - `h-1` => 1px  
  - `h-2` => 2px  
  - `h-3` => 3px  
  - ...  
  - `h-200` => 200px  

**Example**:  
```html
<div class="h-100">This div has a height of 100px.</div>
```

---

#### **2. Height in Viewport Height (vh)**

To set height in viewport height units, use the `h-vh-size` class format followed by a number between **1 and 100**.  
- **Class Format**: `h-vh-<number>`  
- **Usage**:  
  - `h-vh-1` => 1vh  
  - `h-vh-2` => 2vh  
  - `h-vh-3` => 3vh  
  - ...  
  - `h-vh-100` => 100vh  

**Example**:  
```html
<div class="h-vh-50">This div has a height of 50vh.</div>
```

---

#### **3. Height in Percentages (%)**

To set height in percentages, use the `h-p-size` class format followed by a number between **1 and 100**.  
- **Class Format**: `h-p-<number>`  
- **Usage**:  
  - `h-p-1` => 1%  
  - `h-p-2` => 2%  
  - `h-p-3` => 3%  
  - ...  
  - `h-p-100` => 100%  

**Example**:  
```html
<div class="h-p-75">This div has a height of 75%.</div>
```

---

### **Summary Table**

| **Measurement** | **Class Prefix** | **Range**  | **Example**         |
|------------------|------------------|------------|---------------------|
| **Pixels (px)**  | `h-`            | 1 - 200    | `h-50` => 50px     |
| **Viewport (vh)**| `h-vh-`         | 1 - 100    | `h-vh-20` => 20vh  |
| **Percentage (%)**| `h-p-`         | 1 - 100    | `h-p-90` => 90%    |

Use these height utility classes to enhance your layout designs and maintain consistency across your project.


### **Custom CSS Library Documentation: Border and Border Radius Utility Classes**

Our CSS library provides utility classes for styling borders and making rounded elements easily.

---

#### **1. Border Thickness**

To set border thickness in pixels, use the `b-number` class format followed by a number between **1 and 10**.  
- **Class Format**: `b-<number>`  
- **Usage**:  
  - `b-1` => 1px border  
  - `b-2` => 2px border  
  - ...  
  - `b-10` => 10px border  

**Example**:  
```html
<div class="b-3">This div has a border thickness of 3px.</div>
```

---

#### **2. Border Radius**

To set border radius in pixels, use the `br-number` class format followed by a number between **1 and 50**.  
- **Class Format**: `br-<number>`  
- **Usage**:  
  - `br-1` => 1px border radius  
  - `br-2` => 2px border radius  
  - ...  
  - `br-50` => 50px border radius  

**Example**:  
```html
<div class="br-10">This div has a border radius of 10px.</div>
```

---

#### **3. Perfectly Rounded Elements**

To create a perfectly rounded shape (circle), ensure the **height** and **width** are equal, and apply the `r` class to set the radius to **50%**.  
- **Class**: `r`  
- **Usage**:  
  - Combine with height and width classes to form a circle.  

**Example**:  
```html
<div class="w-100 h-100 r">This div is a circle with 100px width and height.</div>
```

---

### **Summary Table**

| **Style**               | **Class Prefix** | **Range**          | **Example**            |
|--------------------------|------------------|--------------------|------------------------|
| **Border Thickness (px)**| `b-`            | 1 - 10             | `b-3` => 3px border   |
| **Border Radius (px)**   | `br-`           | 1 - 50             | `br-20` => 20px radius|
| **Rounded Elements**     | `r`             | Fixed (50% radius) | `w-100 h-100 r` => Circle |

---

### **Usage Examples**

```html
<!-- Border with 5px thickness -->
<div class="b-5">This div has a 5px border.</div>

<!-- Border radius of 25px -->
<div class="br-25">This div has a border radius of 25px.</div>

<!-- A circle with 100px diameter -->
<div class="w-100 h-100 r">This is a circle.</div>
```

These classes make it easy to apply borders and create rounded elements without writing custom CSS.

### **Custom CSS Library Documentation: Flexbox, Grid, and Gap Utility Classes**

### **Updated Documentation: Flexbox Utility Classes**

This section provides a complete overview of the **flexbox utility classes**, including basic setup, directions, alignment, wrapping, and content spacing.

---

### **1. Basic Flexbox Setup**
- **`f`**: Sets `display: flex`.  
**Example**:  
```html
<div class="f">This container uses flexbox.</div>
```

---

### **2. Flex Direction**
- **`fc`**: Flex direction is column (`flex-direction: column;`).  
- **`fc-r`**: Flex direction is column-reverse (`flex-direction: column-reverse;`).  
- **`fr`**: Flex direction is row (`flex-direction: row;`).  
- **`fr-r`**: Flex direction is row-reverse (`flex-direction: row-reverse;`).  

**Example**:  
```html
<div class="f fc">This container stacks items vertically.</div>
```

---

### **3. Flex Wrap**
- **`fw`**: Wraps items to the next line if they exceed container width (`flex-wrap: wrap;`).  
- **`fw-r`**: Wraps items in reverse order (`flex-wrap: wrap-reverse;`).  

**Example**:  
```html
<div class="f fw">This container wraps items to the next line.</div>
```

---

### **4. Alignment and Justification**
#### **Horizontal Alignment (`justify-content`)**
- **`jc`**: Centers content horizontally (`justify-content: center;`).  
- **`jb`**: Space between items (`justify-content: space-between;`).  
- **`ja`**: Space around items (`justify-content: space-around;`).  
- **`je`**: Space evenly distributed (`justify-content: space-evenly;`).  

**Example**:  
```html
<div class="f jc">This container centers content horizontally.</div>
```

#### **Vertical Alignment (`align-items`)**
- **`ac`**: Centers items vertically (`align-items: center;`).  

**Example**:  
```html
<div class="f ac">This container centers items vertically.</div>
```

---

### **5. Content Alignment (`align-content`)**
- **`ac-s`**: Aligns content to the start (`align-content: start;`).  
- **`ac-e`**: Aligns content to the end (`align-content: end;`).  
- **`ac-c`**: Centers content vertically (`align-content: center;`).  
- **`ac-b`**: Adds space between content rows (`align-content: space-between;`).  
- **`ac-a`**: Adds space around content rows (`align-content: space-around;`).  
- **`ac-e`**: Adds space evenly between content rows (`align-content: space-evenly;`).  

**Example**:  
```html
<div class="f fw ac-c">This flex container wraps and centers content vertically.</div>
```

---

### **Quick Reference Table**

| **Feature**              | **Class**       | **Description**                                   |
|---------------------------|-----------------|---------------------------------------------------|
| **Flexbox**              | `f`            | Enables flexbox (`display: flex`).               |
| **Direction**            | `fc`, `fc-r`   | Column or column-reverse.                        |
|                           | `fr`, `fr-r`   | Row or row-reverse.                              |
| **Wrap**                 | `fw`, `fw-r`   | Wrap or wrap-reverse.                            |
| **Horizontal Alignment** | `jc`, `jb`, `ja`, `je` | Horizontal justification options.               |
| **Vertical Alignment**   | `ac`, `ac-s`, `ac-e` | Vertical alignment for items and content.       |
|                           | `ac-c`, `ac-b`, `ac-a` | Advanced vertical content alignment options.    |

---

These utility classes make it easy to create highly flexible and responsive layouts without needing custom CSS.
---

### **2. Grid Utility Classes**

#### **Basic Grid Setup**
- **`grid`**: Sets `display: grid;`.  
**Example**:  
```html
<div class="grid">This container uses grid layout.</div>
```

#### **Grid Columns**
- **`gc`**: 2 auto columns (`grid-template-columns: repeat(2, auto);`).  
- **`gc-3`**: 3 auto columns.  
- **`gc-4`**: 4 auto columns.  
- **`gc-5`**: 5 auto columns.  
- **`gc-6`**: 6 auto columns.  
- **`gc-7`**: 7 auto columns.  

**Example**:  
```html
<div class="grid gc-4">This grid has 4 auto columns.</div>
```

---

### **3. Gap Utility Classes**

#### **Set Gaps Between Elements**
Use `g-<number>` classes to apply gaps in percentages. The range is **1% to 30%**.  

- **Class Format**: `g-<number>`  
- **Usage**:  
  - `g-1` => 1% gap.  
  - `g-2` => 2% gap.  
  - ...  
  - `g-30` => 30% gap.  

**Example**:  
```html
<div class="grid gc-3 g-10">This grid has 3 columns with a 10% gap.</div>
```

---

### **Quick Reference Table**

| **Category**         | **Class**       | **Description**                                  |
|-----------------------|-----------------|--------------------------------------------------|
| **Grid**             | `grid`         | Grid container (`display: grid`).               |
| **Grid Columns**     | `gc`, `gc-3`...| Set column count (2-7).                         |
| **Gap**              | `g-<number>`   | Set gaps between items (1% - 30%).              |

---

These utility classes streamline layout creation, making it quick and intuitive to build responsive designs.
