<template>
  <div class="hero17-header78">
    <div class="hero17-column thq-section-padding thq-section-max-width">
      <div class="hero17-content1">
        <h1 class="hero17-text1 thq-heading-1">
          <slot name="heading1">
            <!--Default content for heading1-->
            <div class="hero17-fragment">
              <span class="hero17-text2">
                Empower Your Game Development Journey
              </span>
            </div>
          </slot>
        </h1>
      </div>
      <div class="hero17-actions"></div>
    </div>
    <div class="hero17-content2">
      <div
        class="hero17-row-container1 thq-animated-group-container-horizontal thq-mask-image-horizontal"
      >
        <div class="hero17-strip1 thq-animated-group-horizontal"></div>
        <div class="thq-animated-group-horizontal">
          <img
            :alt="image1Alt"
            :src="image1Src"
            class="hero17-placeholder-image10 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image2Alt"
            :src="image2Src"
            class="hero17-placeholder-image11 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image3Alt"
            :src="image3Src"
            class="hero17-placeholder-image12 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image4Alt"
            :src="image4Src"
            class="hero17-placeholder-image13 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image5Alt"
            :src="image5Src"
            class="hero17-placeholder-image14 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1534312527009-56c7016453e6?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDIxfHxhYnN0cmFjdHxlbnwwfHx8fDE3MTA4NzA5MzB8MA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero17-placeholder-image15 thq-img-ratio-1-1 thq-img-scale"
          />
        </div>
      </div>
      <div
        class="hero17-row-container2 thq-animated-group-container-horizontal thq-mask-image-horizontal"
      >
        <div class="hero17-strip3 thq-animated-group-horizontal-reverse"></div>
        <div class="thq-animated-group-horizontal-reverse">
          <img
            :alt="image7Alt"
            :src="image7Src"
            class="hero17-placeholder-image16 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image8Alt"
            :src="image8Src"
            class="hero17-placeholder-image17 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image9Alt"
            :src="image9Src"
            class="hero17-placeholder-image18 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image10Alt"
            :src="image10Src"
            class="hero17-placeholder-image19 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            :alt="image11Alt"
            :src="image11Src"
            class="hero17-placeholder-image20 thq-img-ratio-1-1 thq-img-scale"
          />
          <img
            alt="Hero Image"
            src="https://images.unsplash.com/photo-1568214379698-8aeb8c6c6ac8?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDEyfHxncmFmaWN8ZW58MHx8fHwxNzE1Nzk0OTk5fDA&amp;ixlib=rb-4.0.3&amp;w=1500"
            class="hero17-placeholder-image21 thq-img-ratio-1-1 thq-img-scale"
          />
        </div>
      </div>
    </div>
    <div>
      <div class="hero17-container2">
        <DangerousHTML
          html="<style>
    @keyframes scroll-x {
      from {
        transform: translateX(0);
      }
      to {
        transform: translateX(calc(-100% - 16px));
      }
    }
  
    @keyframes scroll-y {
      from {
        transform: translateY(0);
      }
      to {
        transform: translateY(calc(-100% - 16px));
      }
    }
  </style>
  "
        ></DangerousHTML>
      </div>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

export default {
  name: 'Hero17',
  props: {
    image7Alt: {
      type: String,
      default: 'Hero Image',
    },
    image9Alt: {
      type: String,
      default: 'Hero Image',
    },
    image11Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1721333088921-98b778ea472f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image7Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1533739331049-c6a02504f54f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image3Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1529349462515-1def6992a0d6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image4Alt: {
      type: String,
      default: 'Hero Image',
    },
    image8Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1584266032559-fe29c2fc22e8?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image2Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1489850846882-35ef10a4b480?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMHw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image2Alt: {
      type: String,
      default: 'Hero Image',
    },
    image9Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1522069213448-443a614da9b6?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMXw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image11Alt: {
      type: String,
      default: 'Hero Image',
    },
    image5Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1609050470944-59dd791705ac?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image3Alt: {
      type: String,
      default: 'Hero Image',
    },
    image5Alt: {
      type: String,
      default: 'Hero Image',
    },
    image10Alt: {
      type: String,
      default: 'Hero Image',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1561623497-0739a30bebd3?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image10Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1519389950473-47ba0277781c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
    image1Alt: {
      type: String,
      default: 'Game Development Tools',
    },
    image8Alt: {
      type: String,
      default: 'Hero Image',
    },
    image4Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1574781210288-d363a6599df1?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5MTMyMXwwfDF8cmFuZG9tfHx8fHx8fHx8MTczNTAxNTQwMnw&ixlib=rb-4.0.3&q=80&w=1080',
    },
  },
  components: {
    DangerousHTML,
  },
}
</script>

<style scoped>
.hero17-header78 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
 
.hero17-column {
  gap: var(--dl-space-space-oneandhalfunits);
  width: auto;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-unit);
}
 
.hero17-content1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
 
.hero17-text1 {
  text-align: center;
}
 
.hero17-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-unit);
}
 
.hero17-content2 {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
 
.hero17-row-container1 {
  width: 100%;
}
 
.hero17-strip1 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
}
 
.hero17-placeholder-image10 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image11 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image12 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image13 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image14 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image15 {
  width: 400px;
  height: 400px;
}
 
.hero17-row-container2 {
  width: 100%;
}
 
.hero17-strip3 {
  border: 2px dashed rgba(120, 120, 120, 0.4);
}
 
.hero17-placeholder-image16 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image17 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image18 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image19 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image20 {
  width: 400px;
  height: 400px;
}
 
.hero17-placeholder-image21 {
  width: 400px;
  height: 400px;
}
 
.hero17-container2 {
  display: contents;
}
 
.hero17-fragment {
  display: contents;
}
 
.hero17-text2 {
  display: inline-block;
}
 
@media(max-width: 767px) {
  .hero17-content2 {
    width: 100%;
  }
}
 
@media(max-width: 479px) {
  .hero17-actions {
    width: 100%;
    flex-direction: column;
  }
}
</style>
