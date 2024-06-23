# Step 1 : Install Required Packages inside Existing React App

>> `npm install @splidejs/react-splide`

# Step 2 : Import Splide packages into your Component.

>> `import { Splide, SplideSlide } from '@splidejs/react-splide';
>> import '@splidejs/splide/dist/css/splide.min.css';`

# Step 3 : Customize the code as you wish!

>> `<Splide
        options={{
          heightRatio: 0.35,
          type: 'loop',
          perPage: 1,
          perMove: 1,
          focus  : 'center',
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
      </Splide>`

# Step 4: Ensure to specify the correct image source directory.
