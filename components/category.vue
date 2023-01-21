<template>
  <section>
    <div id="vsvhome" class="no-js">
      <div class="vsv-home-group vsv-home-group_dest-she vsv-home-group_5">
        <div
          data-bannerid="9495"
          class="vsv-bannercontainer"
          v-for="(banner, index) in banners"
          :key="index"
        >
          <div
            id="vsv-giftguide-she"
            data-id="9495"
            data-cta="/tr/kadin/one-cikanlar/hediye-rehberi_d20689879"
            data-islinkable="/tr/kadin/one-cikanlar/hediye-rehberi_d20689879"
            class="vsv-box"
          >
            <div class="vsv-blocs">
              <div
                class="vsv-bloc"
                style="background-color: rgba(69, 64, 58, 0.4)"
              >
                <div
                  data-device="desktop,tabletlandscape,tablet"
                  data-akaset=""
                  data-vsvbg="//staticpages.mngbcn.com/homes/images/fw22/she/noviembre/she_landing_gg_0711.jpg"
                  data-vsv-bg-processed="//staticpages.mngbcn.com/homes/images/fw22/she/noviembre/she_landing_gg_0711.jpg?imwidth=429&amp;imdensity=1&amp;impolicy=set_13"
                  class="vsv-image data-vsvbg-50"
                  :style="{
                    'background-image': `url(${banner.imageUrl})`,
                    transition: 'opacity 0.5s ease 0s',
                    opacity: '1',
                  }"
                ></div>
                <div class="vsv-overlay"></div>
                <div class="vsv-bloc-wrapper">
                  <div class="vsv-titles">
                    <h2 class="vsv-title">{{ banner.title }}</h2>
                    <div class="vsv-links">
                      <a
                        href="/tr/kadin/one-cikanlar/hediye-rehberi_d20689879"
                        title="Go to Hediye Rehberi "
                        class="vsv-link"
                        ><span class="hvr-underline-fix2">{{
                          banner.linkText
                        }}</span></a
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="vsv-bannercontainer" data-bannerid="9542">
        <div
          class="vsv-box"
          id="vsv-abrigos-she"
          data-id="9542"
          data-islinkable="/tr/kadin/palto_c67886633"
        ></div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      banners: [
        {
          title: "Yeni",
          backgroundColor: "rgba(255, 255, 255, 0.4)",
          imageUrl:
            "//staticpages.mngbcn.com/homes/images/fw22/she/noviembre/she_newnow_0711_mobile.jpg?imwidth=1292&imdensity=1",
          linkUrl: "/tr/kadin/one-cikanlar/yeni_d18713172",
          linkTitle: "Go to Yeni",
          linkText: "Daha fazla keşfet",
        },
        {
          title: "Another banner",
          backgroundColor: "rgba(255, 255, 255, 0.4)",
          imageUrl:
            "//staticpages.mngbcn.com/homes/images/fw22/she/noviembre/she_newnow_0711_mobile.jpg?imwidth=1292&imdensity=1",
          linkUrl: "/tr/kadin/one-cikanlar/yeni_d18713172",
          linkTitle: "Go to Yeni",
          linkText: "Daha fazla keşfet",
        },
        {
          title: "Another banner",
          backgroundColor: "rgba(255, 255, 255, 0.4)",
          imageUrl:
            "//staticpages.mngbcn.com/homes/images/fw22/she/noviembre/she_newnow_0711_mobile.jpg?imwidth=1292&imdensity=1",
          linkUrl: "/tr/kadin/one-cikanlar/yeni_d18713172",
          linkTitle: "Go to Yeni",
          linkText: "Daha fazla keşfet",
        },
        {
          title: "Another banner",
          backgroundColor: "rgba(255, 255, 255, 0.4)",
          imageUrl:
            "//staticpages.mngbcn.com/homes/images/fw22/she/noviembre/she_newnow_0711_mobile.jpg?imwidth=1292&imdensity=1",
          linkUrl: "/tr/kadin/one-cikanlar/yeni_d18713172",
          linkTitle: "Go to Yeni",
          linkText: "Daha fazla keşfet",
        },
        {
          title: "Another banner",
          backgroundColor: "rgba(255, 255, 255, 0.4)",
          imageUrl:
            "//staticpages.mngbcn.com/homes/images/fw22/she/noviembre/she_newnow_0711_mobile.jpg?imwidth=1292&imdensity=1",
          linkUrl: "/tr/kadin/one-cikanlar/yeni_d18713172",
          linkTitle: "Go to Yeni",
          linkText: "Daha fazla keşfet",
        },
        {
          title: "Another banner",
          backgroundColor: "rgba(255, 255, 255, 0.4)",
          imageUrl:
            "//staticpages.mngbcn.com/homes/images/fw22/she/noviembre/she_newnow_0711_mobile.jpg?imwidth=1292&imdensity=1",
          linkUrl: "/tr/kadin/one-cikanlar/yeni_d18713172",
          linkTitle: "Go to Yeni",
          linkText: "Daha fazla keşfet",
        },
      ],
    };
  },
};
</script>