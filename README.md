- 👋 Hi, I’m @1AceptusMechanicus1

``` html
<ul class="tool-category active" data-tool-category="brush">
        <li><a href="#" data-tool="Brush">Brush</a></li>
        <li><a href="#" data-tool="SphericalBrush">SphericalBrush</a></li>
      </ul>

      <ul class="tool-category" data-tool-category="scissors">
        <li>
          <a href="#" data-tool="FreehandScissors">FreehandScissors</a>
        </li>
        <li>
          <a href="#" data-tool="RectangleScissors">RectangleScissors</a>
        </li>
        <li>
          <a href="#" data-tool="CircleScissors">CircleScissors</a>
        </li>
        <li>
          <a href="#" data-tool="CorrectionScissors">CorrectionScissors</a>
        </li>
        <li>
          <select id="change-scissor-strategy" onchange="changeScissorStrategy(this.value)">
            <option value="fillInside">Fill Inside</option>
            <option value="fillOutside">Fill Outside</option>
            <option value="eraseInside">Erase Inside</option>
            <option value="eraseOutside">Erase Outside</option>
          </select>
        </li>
      </ul>

  ```
