Lingulo-Custom-Select-Boxes
===========================

Example: http://www.lingulo.com/snippet-content/select-boxes/

This script converts your select boxes into CSS3 animated ones. To do so simply follow these instructions:

1. Add a div with the classes "lg-select" and "style1", "style2" or "style3" depending on the style you would like to use (check out the example to choose the style you prefer)
2. Inside "lg-select" add a "span" with the class "lg-placeholder" which should contain the default text for the select box (in our case "Choose Your Dog")
3. Add your select box after the "span" element inside "lg-select"


<div class="lg-select style1">
  <span class="lg-placeholder"><i class="fa fa-paw"></i> Choose Your Dog</span>
  <select>
    <option value="black-labrador">Black Labrador</option>
    <option value="old-english-sheepdog">Old English Sheepdog</option>
    <option value="pomeranian">Pomeranian</option>
    <option value="black-pug">Black Pug</option>
    <option value="white-poodle">White Poodle</option>
    <option value="saint-bernard">Saint Bernard</option>
    <option value="rhodesian-ridgeback">Rhodesian Ridgeback</option>
  </select>
</div>
