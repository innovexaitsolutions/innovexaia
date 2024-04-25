<template>
  <div>
    <!-- Section 1 - Right-aligned image -->
    <section class="hero py-16 bg-gray-100 relative">
      <div class="container mx-auto px-4 flex items-center">
        <div class="w-full text-start">
          <div>
            <h2 class="text-4xl md:text-5xl font-bold mb-4">About Innovexa IT Solutions</h2>
            <p class="text-lg md:text-xl mb-8">
              Innovexa IT Solutions is a leading solutions provider, dedicated to delivering
              innovative solutions to clients. We are committed to providing efficient,
              reliable, and customized technology solutions to businesses, helping them
              achieve their business goals and enhance competitiveness.
            </p>
            <!-- Add any additional content here -->
          </div>
        </div>
      </div>
    </section>

    <!-- Section 2 - Left-aligned image -->
    <section class="py-8">
      <div class="container mx-auto px-4 flex items-center">
        <div class="w-1/2">
          <img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/what_is_image_Processing.jpg" alt="Left Image" class="w-full">
        </div>
        <div class="w-1/2">
          <h2 class="text-3xl font-bold mb-4">Our Business</h2>
          <p class="text-lg">
            Providing Professional Stock Information Consulting Services
          </p>
          <p class="text-lg">
            We provide stock advisory services, covering US stock information, industry
            trends, economic data, financial news, etc. We are committed to offering you
            comprehensive market analysis and investment advice to assist you in making wise
            investment decisions.
          </p>
          <p class="text-lg">
            Whether you are a novice investor or an experienced trader, we can provide you
            with customized services to meet your needs and goals. With our professional
            team and extensive information resources, you will be able to better understand
            the latest trends in the US stock market, seize investment opportunities, and
            achieve your financial goals.
          </p>
        </div>
      </div>
    </section>

    <!-- Section 3 - Right-aligned image -->
    <section class="py-8 bg-gray-100">
      <div class="container mx-auto px-4 flex items-center">
        <div class="w-1/2">
          <h2 class="text-3xl font-bold mb-4">The Information of US Stocks</h2>
          <p class="text-lg">
            US Stocks refers to stocks or shares of publicly traded companies that are
            listed on stock exchanges in the United States, such as the New York Stock
            Exchange (NYSE) or the NASDAQ Stock Market.
          </p>
          <p class="text-lg">
            These stocks represent ownership stakes in companies and can be bought and sold
            by investors through brokerage firms.
          </p>
          <p class="text-lg">
            Investing in US stocks provides individuals with the opportunity to participate
            in the ownership and potential profits of American companies.
          </p>
        </div>
        <div class="w-1/2">
          <img src="https://img.freepik.com/free-photo/painting-mountain-lake-with-mountain-background_188544-9126.jpg" alt="Right Image" class="w-full">
        </div>
      </div>
    </section>

    <!-- Section 4 - Left-aligned image -->
    <section class="py-8">
      <div class="container mx-auto px-4 flex items-center">
        <div class="w-1/2">
          <img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/what_is_image_Processing.jpg" alt="Left Image" class="w-full">
        </div>
        <div class="w-1/2">
          <h2 class="text-3xl font-bold mb-4">Why invest in the U.S. Market?</h2>
          <ul class="list-disc pl-6">
            <li class="text-lg">Better capitalization</li>
            <li class="text-lg">More liquidity</li>
            <li class="text-lg">Greater diversification</li>
            <li class="text-lg">Market transparency</li>
            <li class="text-lg">Lower currency risk</li>
            <li class="text-lg">Innovation</li>
          </ul>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style scoped>
/* Add any custom styles here */
.container {
  max-width: 960px;
}

/* Adjust styles for images */
img {
  display: block;
  max-width: 100%;
  height: auto;
}

.hero {
  /* Adjust the height of the hero section */
  height: 500px;
  background-image: url('https://img.freepik.com/free-photo/painting-mountain-lake-with-mountain-background_188544-9126.jpg');
  color: #ffffff;
}

.hero h2 {
  /* Adjust font size and spacing */
  letter-spacing: -0.025em;
}

.hero p {
  /* Adjust font size and line height */
  line-height: 1.5;
}

</style>
