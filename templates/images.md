# Two images side by side

<div class="grid grid--p-3">
  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="/assets/images/main_window.png">
        <img src="/assets/images/main_window.png" style="width: 100%; height: auto;" alt="Main window" />
      </a>
      <figcaption style="text-align: center;">Screenshot 1</figcaption>
    </figure>
  </div>
  <div class="cell cell--12 cell--md-6">
    <figure>
      <a data-gallery href="/assets/images/main_window.png">
        <img src="/assets/images/main_window.png" style="width: 100%; height: auto;" alt="Main window" />
      </a>
      <figcaption style="text-align: center;">Screenshot 1</figcaption>
    </figure>
  </div>
</div> 


# One image centered

<div class="cell cell--12 cell--md-6">
  <figure>
    <a data-gallery href="/assets/images/main_window.png">
      <img src="/assets/images/main_window.png" style="display: block; margin: 0 auto; max-width: 100%;" alt="Main window" />
    </a>
    <figcaption style="text-align: center;">Screenshot 1</figcaption>
  </figure>
</div>

# New format :

{% include image.html
   src="/assets/images/docs/fr/calibration_tool/calibration_tool.PNG"
   alt="Outil de calibration"
   max_width="50%" %}

OR with caption

{% include image.html
   src="/assets/images/docs/fr/calibration_tool/calibration_tool.PNG"
   alt="Outil de calibration"
   max_width="50%"
   caption="Outil de calibration – ajustement du volant" %}


