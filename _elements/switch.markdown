---
title: Switch
description: Now you can tell your users to flip the switch or switch off.
code:
  javascript:
  html: |
    <div class="switch tiny">
      <input class="switch-input" id="tinySwitch" type="checkbox" name="exampleSwitch">
      <label class="switch-paddle" for="tinySwitch">
        <span class="show-for-sr">Tiny Sandwiches Enabled</span>
      </label>
    </div>

    <div class="switch small">
      <input class="switch-input" id="smallSwitch" type="checkbox" name="exampleSwitch">
      <label class="switch-paddle" for="smallSwitch">
        <span class="show-for-sr">Small Portions Only</span>
      </label>
    </div>

    <div class="switch large">
      <input class="switch-input" id="largeSwitch" type="checkbox" name="exampleSwitch">
      <label class="switch-paddle" for="largeSwitch">
        <span class="show-for-sr">Show Large Elephants</span>
      </label>
    </div>
  markdown:
---
{% include code.markdown %}
