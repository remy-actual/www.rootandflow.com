---
title: Orbit
description: An image and content carousel with animation support and many customizable options.
code:
  javascript:
  html: |
    <div class="orbit" role="region" aria-label="Favorite Space Pictures" data-orbit>
      <ul class="orbit-container">
        <button class="orbit-previous" aria-label="previous"><span class="show-for-sr">Previous Slide</span>&#9664;</button>
        <button class="orbit-next" aria-label="next"><span class="show-for-sr">Next Slide</span>&#9654;</button>
        <li class="is-active orbit-slide">
          <div>
            <h3 class="text-center">You can also throw some text in here!</h3>
            <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde harum rem, beatae ipsa consectetur quisquam. Rerum ratione, delectus atque tempore sed, suscipit ullam, beatae distinctio cupiditate ipsam eligendi tempora expedita.</p>
            <h3 class="text-center">This Orbit slide has chill</h3>
          </div>
        </li>
        <li class="orbit-slide">
          <div>
            <h3 class="text-center">You can also throw some text in here!</h3>
            <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde harum rem, beatae ipsa consectetur quisquam. Rerum ratione, delectus atque tempore sed, suscipit ullam, beatae distinctio cupiditate ipsam eligendi tempora expedita.</p>
            <h3 class="text-center">This Orbit slide has chill</h3>
          </div>
        </li>
        <li class="orbit-slide">
          <div>
            <h3 class="text-center">You can also throw some text in here!</h3>
            <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde harum rem, beatae ipsa consectetur quisquam. Rerum ratione, delectus atque tempore sed, suscipit ullam, beatae distinctio cupiditate ipsam eligendi tempora expedita.</p>
            <h3 class="text-center">This Orbit slide has chill</h3>
          </div>
        </li>
        <li class="orbit-slide">
          <div>
            <h3 class="text-center">You can also throw some text in here!</h3>
            <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde harum rem, beatae ipsa consectetur quisquam. Rerum ratione, delectus atque tempore sed, suscipit ullam, beatae distinctio cupiditate ipsam eligendi tempora expedita.</p>
            <h3 class="text-center">This Orbit slide has chill</h3>
          </div>
        </li>
      </ul>
      <nav class="orbit-bullets">
       <button class="is-active" data-slide="0"><span class="show-for-sr">First slide details.</span><span class="show-for-sr">Current Slide</span></button>
       <button data-slide="1"><span class="show-for-sr">Second slide details.</span></button>
       <button data-slide="2"><span class="show-for-sr">Third slide details.</span></button>
       <button data-slide="3"><span class="show-for-sr">Fourth slide details.</span></button>
     </nav>
    </div>
  markdown:
---
{% include code.markdown %}
