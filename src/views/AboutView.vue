<script setup>
import heroImage from '@/assets/images/heroImage.jpg';
import team from '@/assets/images/team.jpg';
import apart from '@/assets/images/apart.jpg';
</script>

<template>
  <div class="pt-20 bg-black opacity-90 text-white">
    <div class="w-[85%] lg:w-[75%] mx-auto py-16">
      <div class="text-center">
        <h3 class="text-4xl mb-10">Welcome to Skyline Home Group</h3>
        <p class="text-lg">
          At Skyline Home Group, we're dedicated to providing exceptional real
          estate services to our clients in the New York metropolitan area,
          including New York City and New Jersey. With years of experience and
          unparalled knowledge of the market, our team is committed to helping
          you achieve your realestate goals
        </p>
      </div>
      <div class="py-20">
        <!--================Our Mission -->
        <div class="grid lg:grid-cols-2 gap-10 mb-20">
          <div class="w-full max-h-[600px] lg:max-h-[400px]">
            <img :src="heroImage" alt="" class="w-full h-full object-cover" />
          </div>
          <div>
            <h3 class="text-4xl mb-8">Our Mission</h3>
            <p class="text-xl font-[200] leading-[2]">
              Our mission is to deliver personalized, results-driven service to
              each and every client. We strive to build long-lasting
              relationships founded on trust, expertise, and a passion for the
              communities we serve.
            </p>
          </div>
        </div>
        <!--================Our Team -->
        <div class="grid lg:grid-cols-2 gap-10 mb-20">
          <div>
            <h3 class="text-4xl mb-8">Our Team</h3>
            <p class="text-xl font-[200] leading-[2]">
              Our team of seasoned real estate professionals is comprised of
              local experts who possess intimate knowledge of the neighborhoods,
              communities, and market trends in New York Cit and New Jersey.
              From the bright lights of Manhattan to the charming suburbs of the
              Garden State, we know every corner of the region
            </p>
          </div>

          <div class="w-full max-h-[600px] lg:max-h-[400px]">
            <img
              :src="team"
              alt="Our Team"
              class="w-full h-full object-cover"
            />
          </div>
        </div>
        <!--================What Sets Us Apart -->
        <div class="grid lg:grid-cols-2 gap-10">
          <div class="w-full max-h-[600px] lg:max-h-[400px]">
            <img
              :src="apart"
              alt="What Sets Us Apart"
              class="w-full h-full object-cover"
            />
          </div>
          <div>
            <h3 class="text-4xl mb-8">What Sets Us Apart</h3>
            <ul class="text-xl font-[200] leading-[2]">
              <li class="list-disc">
                unparalled market knowledge and expertise in New York City and
                New Jersey
              </li>
              <li class="list-disc">
                Personalized service tailored to each clients unique needs
              </li>
              <li class="list-disc">
                Proven track record of success in the competitive NYC and NJ
                real estated markets
              </li>
              <li class="list-disc">
                Commitment to integrity, transparency, and exceptional
                communication
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
