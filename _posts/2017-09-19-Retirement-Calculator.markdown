---
layout: single
excerpt: "Retirement Calculator"
category: articles
header:
  teaser: /assets/images/hello-world.jpg
  overlay_image: /assets/images/hello-world.jpg
  overlay_filter: 0.2 # same as adding an opacity of 0.5 to a black background
styles: ["/assets/css/bootstrap.min.css", "/assets/css/vuetify.css"]
scripts: ["https://unpkg.com/vue/dist/vue.js", "https://unpkg.com/vuetify/dist/vuetify.js"]
---

# Retirement calculator



<div class="container" markdown="1">
# Testing
</div>
<div id="app">
   <v-app>
     <main>
       <v-container grid-list-md>
        <v-layout column>
          <v-flex>
            <v-layout>
              <v-flex>
                <div class="input-group input-group-lg">
                  <span class="input-group-addon" id="sizing-addon1">@</span>
                  <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="sizing-addon1">
                </div>
              </v-flex>
              <v-flex>
                <div class="input-group">
                  <span class="input-group-addon" id="sizing-addon2">@</span>
                  <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="sizing-addon2">
                </div>
              </v-flex>
            </v-layout>
          </v-flex>

          <v-flex>
            <v-layout>
              <v-flex>
                <div class="input-group input-group-lg">
                  <span class="input-group-addon" id="sizing-addon1">@</span>
                  <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="sizing-addon1">
                </div>
              </v-flex>
              <v-flex>
                <div class="input-group">
                  <span class="input-group-addon" id="sizing-addon2">@</span>
                  <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="sizing-addon2">
                </div>
              </v-flex>
            </v-layout>
          </v-flex>
        </v-layout>
       </v-container>
     </main>
   </v-app>
 </div>

 <div class="row">
  <div class="col">
    <div class="input-group">
      <span class="input-group-addon" id="sizing-addon1">@</span>
      <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="sizing-addon1">
    </div>
  </div>
  <div class="col">
    <div class="input-group">
      <span class="input-group-addon" id="sizing-addon2">@</span>
      <input type="text" class="form-control" placeholder="Username" aria-label="Username" aria-describedby="sizing-addon2">
    </div>
  </div>
 </div>

 <script>
 new Vue({ el: '#app' })
 </script>
