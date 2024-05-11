# Home Quest

## Topic

I chose the topic "Home Quest" because it reflects my extensive past experiences and my current efforts to help people purchase homes. My real estate journey started quite unexpectedly when I was a project manager at an online real estate company. This role sparked my interest so deeply that I went on to get my real estate license. However, I have remained in the IT field, where I have built a career over the last 15 years, and which continues to be my greatest passion. Today, I use my diverse set of skills to assist friends and family as they tackle the complexities of buying property in California. My involvement goes beyond mere transactions; I am committed to helping people make well-informed, stress-free decisions as they search for their ideal home and fulfillment of the American Dream. Born out of this commitment, "Home Quest" seeks to empower others by providing educational and personalized support throughout their home-buying process.

Here's how you could update the Markdown document based on the HTML code provided for the Home Quest website:

git # Home Quest Website

### Navigation Menu

- **Home:** The starting point of the website where users can access all resources and navigate to specific sections of interest.
- **Home Guide Journey:** This page offers a step-by-step guide through the home building or buying process. It covers everything from selecting a location, designing your home, choosing contractors, and understanding legal requirements.
- **Financial Insights:** Provides valuable information on managing the financial aspects of building or buying a home. Topics include budgeting for a new build, financing options, cost-saving tips, and navigating mortgages and loans.
- **Construction Basics:** Detailed examinations of different materials and methods used in home construction. This page is divided into sections like Foundations, Siding, and Roof Types, providing pros, cons, and cost considerations for each.
- **About:** Gives background information about Home Quest, including its mission, history, and the team behind it. It may also include testimonials from users or case studies demonstrating the practical application of the information provided on the website.

#### Header Navigation Menu

For the website's navigation, I am using a flex container to align the navigation links horizontally and ensure they are evenly distributed across the header. This not only makes the navigation appear organized, but also makes it easily scalable as new pages are added.

```css
nav ul {
  display: flex;
  list-style: none;
  align-items: center;
  flex-wrap: wrap;
}
nav ul li {
  margin: 1em;
  flex-grow: 1;
  text-align: center;
  min-width: 120px;
  padding: 5px 10px;
}
```

#### Flexbox Usage in Build.html

Flexbox is used on the `build.html` and `guide.html` pages of the Home Quest website to create responsive and adaptable layouts that adjust smoothly across different devices by responding to the devices screen size. This ensures a consistent and user-friendly experience for all visitors. On `build.html`, Flexbox neatly arranges sections like Foundations, Siding, and Roof Types into clean, responsive boxes. On `guide.html`, it structures the navigation and main content for clear and easy navigation, and adapts the 'Step-by-Step Home Buying Guide' layout boosting user accessibility.

```css
.box-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.box {
  flex: 1 1 250px; // Allows the box to grow and shrink with a base width of 250px
  margin: 10px;
  padding: 20px;
  border-radius: 8px;
  min-height: 100px;
  box-shadow: 1px 5px 10px rgba(0, 0, 0, 0.3);
}
```

## Media

For Media I decided to use the Common Media Query Breakpoint:

### Common Media Query breakpoints:

| Breakpoint         | Description             |
| ------------------ | ----------------------- |
| < 481px            | Mobile devices          |
| 481px — 768px      | iPads, Tablets          |
| 769px — 1024px     | Small screens, laptops  |
| 1025px — 1200px    | Desktops, large screens |
| 1201px and greater | Extra large screens, TV |
