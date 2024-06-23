## Step 1: Install Required Packages within Your Existing React App

\`\`\`bash
npm install @splidejs/react-splide
\`\`\`

## Step 2: Import Splide Components and CSS

\`\`\`javascript
import { Splide, SplideSlide } from '@splidejs/react-splide';
import '@splidejs/splide/dist/css/splide.min.css';
\`\`\`

## Step 3: Customize Your Slider

\`\`\`jsx
<Splide
  options={{
    heightRatio: 0.35,
    type: 'loop',
    perPage: 1,
    perMove: 1,
    focus: 'center',
    autoplay: true,
    autoScroll: {
      speed: 1,
    },
    interval: 2500
  }}
>
  <SplideSlide>
    <img src="./image1.jpg" alt="Slide 1" />
  </SplideSlide>

  <SplideSlide>
    <img src="./image2.jpg" alt="Slide 2" />
  </SplideSlide>

  <SplideSlide>
    <img src="./image3.jpg" alt="Slide 3" />
  </SplideSlide>
</Splide>
\`\`\`

## Step 4: Specify Correct Image Source Directory

Ensure that the image paths (\`./image1.jpg\`, \`./image2.jpg\`, \`./image3.jpg\`) are correctly specified based on your project's directory structure.
