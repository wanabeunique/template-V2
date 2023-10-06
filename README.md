## template for creating websites on html, css, js
### Features: folders structure width css/js/html; diffrent containers (width left/right padding and other in _containers.sass); variables for colors, offsets, etc.; js tabs, accordion; shrek image for test; footer always at the bottom of the page (if page < 100vh)


- tabs

    + connect
        ```html
            <script defer src="./../js/tabs.js"></script>
        ```
    
    + template
        ```js
            <div class="tabs">
              <div class="tabs__top">
                <div class="tabs__top--item active-select">tab1</div>
                <div class="tabs__top--item">tab1</div>
              </div>
              <div class="tabs__content">
                <div class="tabs__content--item active-tab">content1</div>
                <div class="tabs__content--item">content2</div>
              </div>
            </div>
        ```

- accordion

    + connect
        ```html
          <script defer src="./../js/accordion.js"></script>
        ```
    
    + template
        ```html
        <div class="accordion">
            <div class="accordion__top">
                accordion preview
             </div>
            <div class="accordion__content">
                accordion content
            </div>
        </div>
        ```

