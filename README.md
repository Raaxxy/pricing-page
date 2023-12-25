
## 🎨 Design Requirements

## Components:

### 2.1. Page Container:

- `id`: `page-container`
- Background color: Light gray (`bg-gray-200`).
- Full-width container.
- Centralized content: `mx-auto`.

### 2.2. Header Section:

- Use the appropriate semantic tag.
- Text alignment: Centered.
- Title:
  - Text: "Pricing".
  - Font size: Large (`text-4xl`).
  - Font weight: Medium.
- Subtitle:
  - Text: "Signup for a free 14-day trial today! No Payment needed."
  - Font size: Medium-large (`text-lg`).
  - Color: Dark gray (`text-gray-700`).
  - Margin top: 2 units.
  - Horizontal padding: 6 units on both sides.
- Decorative Line Below Subtitle:
  - Horizontal alignment: Centered.
  - Color: Pink-500 (`bg-pink-500`)
  - Width: `w-24`
  - Opacity: 75%
  - Rounded corners
  - Margin top: 4 units.

### 2.3. Pricing Cards:

Each card should include the following:

- Card Title (Plan name).
- Monthly price
- Brief description.
- List of features.
- A call to action button.

#### 2.3.1. Basic Card:

- id attribute: `basic-pricing-card`
- Background: White.
- Text color: Black.
- Shadow: Medium.
- Border top: Gray-100.
- Title: "BASIC"
- Price: "$7/mo"

#### 2.3.2. Plus Card (Most Popular):

- id attribute: `popular-pricing-card`
- All the properties from the Basic card.
- Title: "PLUS"
- Price: "$15/mo"
- Highlight banner at the top with text "Most Popular".
  - Text size: Small (`text-sm`).
  - Text color: White (`text-white`).
  - Background color: Pink-500 (`bg-pink-500`).
  - Font weight: Semibold.
  - Uppercase text.
  - Padding: Vertical 4 units.

#### 2.3.3. Pro Card:

- id attribute: `pro-pricing-card`
- Similar properties to the Basic card.
- Title: "PRO"
- Price: "$30/mo"

### 2.4. Features Icon:

- Use the provided SVG with a green checkmark.

  ```html
  <svg
    class="w-6 h-6 align-middle"
    width="24"
    height="24"
    viewBox="0 0 24 24"
    fill="none"
    stroke="currentColor"
    stroke-width="2"
    stroke-linecap="round"
    stroke-linejoin="round"
  >
    <path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path>
    <polyline points="22 4 12 14.01 9 11.01"></polyline>
  </svg>
  ```

- Surrounding circle: Rounded full (`rounded-full`).
- Padding: 2 units (`p-2`).
- Fill color: Green-700.

### 2.5. Call to Action Button:

- Background: Indigo-500 (`bg-indigo-500`).
- Font size: Large (`text-lg`).
- Font weight: Semibold.
- Text color: White.
- Rounded corners.
- Padding: Vertical 3 units, Horizontal 6 units.
- Shadow: Extra large.
- Hover effect: Background color transitions to Indigo-600.
