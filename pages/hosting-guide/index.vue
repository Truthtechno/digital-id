<template>
  <div class="bg-gray-900 mx-auto text-gray-100" style="max-width: 960px">
    <div class="px-4">
      <div class="flex items-start justify-between pt-8">
        <NuxtLink to="/">
          <div
            class="logo w-24"
            v-html="require(`~/assets/icons/logo.svg?include`)"
            title="XEN Digital Card Generator"
          ></div
        ></NuxtLink>
        <a
          class="font-extrabold tracking-wide leading-none shrink-0 p-3 border-2 text-white border-gray-700 rounded hover:bg-gray-700 focus:bg-gray-700 transition-colors duration-200"
          href="https://wa.me/+256766704533"
          target="_blank"
          >CONTACT US</a
        >
      </div>
      <div id="guide" class="max-w-screen-sm">
        <h1
          class="text-3xl md:text-5xl font-extrabold mt-24 md:mt-48 md:leading-tight"
        >
        Hosting Guide for Businesses
        </h1>
        <h2 class="mt-8 text-lg md:text-xl w-full md:w-3/4 text-gray-200">
          Follow these instructions to get your Digital Business online.
        </h2>

        <p class="mt-16 border px-4 py-3 rounded border-gray-700">
          The digital card files are in the folder you just extracted
          from your downloaded ZIP file. This folder will be referred to as the
          "<span class="font-extrabold">Business-ID folder</span>" throughout this
          guide.
        </p>

        <div class="mt-16">
          <h3 class="font-extrabold text-2xl">
            Option 1: Hosting on a Business Website (WordPress Users)
          </h3>
          <ul class="px-6 mt-6 list-outside list-disc">
            <li>
              Login to your cPanel account. Locate and open the file manager.
            </li>
            <li>
              Locate the public_html folder & create a new folder called BusinessID.
            </li>
            <li>
              Upload your Business-ID folder inside the new folder.
            </li>
            <li>
              Your Digital Business ID system is now online at: https://your-Business.com/BusinessID/username/
            </li>
          </ul>
        </div>

        <div class="mt-16">
          <h3 class="font-extrabold text-2xl">
            Option 2: Hosting on a Business Server
          </h3>
          <ul class="px-6 mt-6 list-outside list-disc">
            <li>
              Suitable for Business with their own IT infrastructure.
            </li>
            <li>
              Can be integrated with the company management system.
            </li>
          </ul>
        </div>
       <!-- <div class="mt-16">
          
          <h3 class="font-extrabold text-2xl">
            Our website is maintained by a developer
          </h3>
          <ul class="px-6 mt-6 list-outside list-disc">
            <li>
              Contact our developers to host the business card for you. Just
              send them the downloaded ZIP file.
            </li>
          </ul>
        </div> 
        <div class="mt-16">
          <h3 class="font-extrabold text-2xl">
            We as well offer Hosting & Maintenance services with a reliable IT Team
          </h3>
          <ul class="px-6 mt-6 list-outside list-disc">
            <li>
              Share the zip file details with our IT team at
              <NuxtLink
                to="/"
                class="underline font-extrabold text-yellow-500 hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
                >XEN CAPITAL PARTNERS LTD</NuxtLink
              >.
            </li>
            <li>
              If you got some business cards created by yourself, contact your
              IT team to host it for you. Just send them the downloaded ZIP
              files and share the link to this
              <a
                class="underline font-extrabold text-yellow-500 hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
                href="https://enbizcard.vishnuraghav.com/hosting-guide"
                target="_blank"
                >Hosting Guide</a
              >.
            </li>
          </ul>
        </div>
        <div class="mt-16">
          <h3 class="font-extrabold text-2xl">
            I'm the developer / administrator of a website
          </h3>
          <ul class="px-6 mt-6 list-outside list-disc">
            <li>
              Create a folder called "vcard" ( or whatever you like ) in the
              project's static folder.
            </li>
            <li>Copy the Business-Card folder inside the "vcard" folder.</li>
            <li>Commit changes and deploy.</li>
            <li>
              Now the business card should be online at the address
              https://your-domain/vcard/bizcard-folder/ and is ready to be
              shared.
            </li>
          </ul>
        </div>
        <div class="mt-16">
          <h3 class="font-extrabold text-2xl">I don't have a website</h3>
          <p class="mt-6">
            You can host your digital business card using several free hosting
            services available such as
            <a
              class="underline font-extrabold text-yellow-500 hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
              href="https://surge.sh"
              target="_blank"
              rel="noopener noreferrer"
              >Surge</a
            >,
            <a
              class="underline font-extrabold text-yellow-500 hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
              href="https://pages.github.com/"
              target="_blank"
              rel="noopener noreferrer"
              >GitHub Pages</a
            >,
            <a
              class="underline font-extrabold text-yellow-500 hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
              href="https://docs.gitlab.com/ee/user/project/pages/"
              target="_blank"
              rel="noopener noreferrer"
              >GitLab Pages</a
            >, etc.
          </p>
          <ul class="px-6 mt-6 list-outside list-disc">
            <li>
              Follow the user guide of any of the services mentioned above to
              setup a website.
            </li>
            <li>
              Once done, copying your Business-Card folder into a respective folder is
              all it needed to get your digital business card online. But the
              procedure might vary with platform.
            </li>
          </ul>
          <p class="mt-4">
            If you got any doubt setting up your digital business card on any of
            these platforms, You can always
            <a
              class="underline text-yellow-500 font-extrabold hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
              href="https://t.me/enbizcard"
              target="_blank"
              rel="noopener noreferrer"
              >join the telegram group</a
            >
            and ask it.
          </p>
        </div>-->
        <div class="mt-16">
          <h3 class="font-extrabold text-2xl">
            Updating Digital Business Cards
          </h3>
          <p class="mt-6">
            This system currently does not store any data online for you to retrieve it for
            editing. So, every card has to be manually corrected from the generated HTML or 
            regenerated.
          </p>
          <ul class="px-6 mt-6 list-outside list-disc">
            <li>
              Visit
              <NuxtLink
                to="/"
                class="font-extrabold text-yellow-500 hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
                >XEN DIGITAL ID GENERATOR</NuxtLink
              >
              and generate a new Digital Business Card.
            </li>
            <li>
              Extract the downloaded ZIP file and copy your Business-ID folder
              containing your updated files.
            </li>
            <li>
              Follow the exact same steps as listed above to
              update the digital card being changed.
            </li>
          </ul>
        </div>
       <!-- <div class="mt-16">
          <h3 class="font-extrabold text-2xl">
            How do I add another business card to my website?
          </h3>
          <ul class="px-6 mt-6 list-outside list-disc">
            <li>
              Visit
              <NuxtLink
                to="/"
                class="underline font-extrabold text-yellow-500 hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
                >EnBizCard</NuxtLink
              >
              and generate a Digital Business card.
            </li>
            <li>
              Extract the downloaded ZIP file and copy the Business-Card folder.
            </li>
            <li>
              Follow the exact same steps as per your category listed above to
              add the  Digital Business card.
            </li>
            <li>
              Place the copied folder inside the same folder where you already
              have your Business-Card folders.
            </li>
          </ul>
        </div>-->
      </div>
      <Help />
     <!-- <div class="mt-24">
        Help me improve this guide on
        <a
          class="underline text-yellow-500 font-extrabold hover:text-yellow-300 focus:text-yellow-300 transition-colors duration-200"
          href="https://github.com/vishnuraghavb/EnBizCard"
          target="_blank"
          rel="noopener noreferrer"
          >GitHub</a
        >
      </div>-->
    </div>
    <Footer />
  </div>
</template>
<script>
import Footer from '@/components/Footer'
import Help from '@/components/Help'

export default {
  components: {
    Footer,
    Help,
  },
}
</script>