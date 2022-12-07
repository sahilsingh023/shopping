<template>
    <div>
        <div class="container-fluid">
<!-- side bar -->
<div class="row">
    <div class="col-md-2 col-12 sidebar-main">
        <div class="sidebar-header"><h3 class="font-bold">Filter</h3></div> <div class="applied-filter" style="display:none;"><h3>Applied Filters</h3> <ul></ul> <a href="#" class="filter-clear"><span>Clear All</span></a></div>
        <div class="accordion" id="accordionExample">

            <div class="accordion-item">
              <h2 class="accordion-header" id="headingOne">
              <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">  Category </button>
              </h2>
              <div id="collapseOne" class="accordion-collapse collapse" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  
                   <ul class="list-unstyled mobile-active" style="list-style-type:square;">
                      <li class="kurtas">
                        <a
                          href="#"
                          value="Category_Kurtas"
                          style="display: "
                          class=""
                          ><span>Kurtas</span>
                          <span class="filtertotal" style="display: "
                            >(2209)</span
                          ></a
                        >
                      </li>
                      <li class="sets-_-dresses">
                        <a
                          href="#"
                          value="Category_Sets &amp; Dresses"
                          style="display: "
                          class=""
                          ><span>Sets &amp; Dresses</span>
                          <span class="filtertotal" style="display: "
                            >(11)</span
                          ></a
                        >
                      </li>
                      <li class="top-wear-_-kurtas">
                        <a
                          href="#"
                          value="Category_TOP WEAR > KURTAS"
                          style="display: "
                          class=""
                          ><span>TOP WEAR &gt; KURTAS</span>
                          <span class="filtertotal" style="display: "
                            >(2)</span
                          ></a
                        >
                      </li>
                      <li class="tops">
                        <a
                          href="#"
                          value="Category_Tops"
                          style="display: "
                          class=""
                          ><span>Tops</span>
                          <span class="filtertotal" style="display: "
                            >(1)</span
                          ></a
                        >
                      </li>
                    </ul>
                </div>
              </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingTwo">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                   Price
                  </button>
                </h2>
                <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                  <div class="accordion-body">
                    <ul class="list-unstyled" style="list-style-type:square;">
                        <li class="0,2000">
                          <a
                            href="#"
                            value="Price_Rs.0 to Rs.2000"
                            style="display: "
                            class=""
                            ><span>Rs.0 to Rs.2000</span>
                            <span class="filtertotal" style="display: "
                              >(1590)</span
                            ></a
                          >
                        </li>
                        <li class="2000,4000">
                          <a
                            href="#"
                            value="Price_Rs.2000 to Rs.4000"
                            style="display: "
                            class=""
                            ><span>Rs.2000 to Rs.4000</span>
                            <span class="filtertotal" style="display: "
                              >(774)</span
                            ></a
                          >
                        </li>
                        <li class="4000,6000">
                          <a
                            href="#"
                            value="Price_Rs.4000 to Rs.6000"
                            style="display: "
                            class=""
                            ><span>Rs.4000 to Rs.6000</span>
                            <span class="filtertotal" style="display: "
                              >(126)</span
                            ></a
                          >
                        </li>
                        <li class="6000,8000">
                          <a
                            href="#"
                            value="Price_Rs.6000 to Rs.8000"
                            style="display: "
                            class=""
                            ><span>Rs.6000 to Rs.8000</span>
                            <span class="filtertotal" style="display: "
                              >(17)</span
                            ></a
                          >
                        </li>
                      </ul>
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header" id="headingThree">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                    Discount
                  </button>
                </h2>
                <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                  <div class="accordion-body">
                    
                    <ul class="list-unstyled" style="list-style-type:square;">
                        <li class="30">
                          <a
                            href="#"
                            value="Discount_30%"
                            style="display: "
                            class=""
                            ><span>30%</span>
                            <span class="filtertotal" style="display: "
                              >(21)</span
                            ></a
                          >
                        </li>
                        <li class="40">
                          <a
                            href="#"
                            value="Discount_40%"
                            style="display: "
                            class=""
                            ><span>40%</span>
                            <span class="filtertotal" style="display: "
                              >(5)</span
                            ></a
                          >
                        </li>
                        <li class="5">
                          <a href="#" value="Discount_5%" style="display: " class=""
                            ><span>5%</span>
                            <span class="filtertotal" style="display: "
                              >(1)</span
                            ></a
                          >
                        </li>
                        <li class="60">
                          <a
                            href="#"
                            value="Discount_60%"
                            style="display: "
                            class=""
                            ><span>60%</span>
                            <span class="filtertotal" style="display: "
                              >(1)</span
                            ></a
                          >
                        </li>
                        <li class="70">
                          <a
                            href="#"
                            value="Discount_70%"
                            style="display: "
                            class=""
                            ><span>70%</span>
                            <span class="filtertotal" style="display: "
                              >(10)</span
                            ></a
                          >
                        </li>
                      </ul>

                    
                  </div>
                </div>
              </div>

              <div class="accordion-item">
                <h2 class="accordion-header" id="heading4">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse4" aria-expanded="false" aria-controls="collapse4">
                    Colour
                  </button>
                </h2>
                <div id="collapse4" class="accordion-collapse collapse" aria-labelledby="heading4" data-bs-parent="#accordionExample">
                  <div class="accordion-body">
                    
                    <ul class="list-unstyled" style="list-style-type:square;">
                        <li class="-yellow">
                          <a href="#" value="Colour_ Yellow" style="display: " class=""
                            ><span> Yellow</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="beige">
                          <a href="#" value="Colour_Beige" style="display: " class=""
                            ><span>Beige</span>
                            <span class="filtertotal" style="display: ">(121)</span></a
                          >
                        </li>
                        <li class="black">
                          <a href="#" value="Colour_Black" style="display: " class=""
                            ><span>Black</span>
                            <span class="filtertotal" style="display: ">(136)</span></a
                          >
                        </li>
                        <li class="blue">
                          <a href="#" value="Colour_Blue" style="display: " class=""
                            ><span>Blue</span>
                            <span class="filtertotal" style="display: ">(471)</span></a
                          >
                        </li>
                        <li class="brown">
                          <a href="#" value="Colour_Brown" style="display: " class=""
                            ><span>Brown</span>
                            <span class="filtertotal" style="display: ">(57)</span></a
                          >
                        </li>
                        <li class="coral">
                          <a href="#" value="Colour_Coral" style="display: " class=""
                            ><span>Coral</span>
                            <span class="filtertotal" style="display: ">(3)</span></a
                          >
                        </li>
                        <li class="cream">
                          <a href="#" value="Colour_Cream" style="display: " class=""
                            ><span>Cream</span>
                            <span class="filtertotal" style="display: ">(40)</span></a
                          >
                        </li>
                        <li class="dark-blue">
                          <a href="#" value="Colour_Dark Blue" style="display: " class=""
                            ><span>Dark Blue</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="dark-brown">
                          <a href="#" value="Colour_Dark Brown" style="display: " class=""
                            ><span>Dark Brown</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="dark-green">
                          <a href="#" value="Colour_Dark Green" style="display: " class=""
                            ><span>Dark Green</span>
                            <span class="filtertotal" style="display: ">(2)</span></a
                          >
                        </li>
                        <li class="dark-purple">
                          <a href="#" value="Colour_Dark Purple" style="display: " class=""
                            ><span>Dark Purple</span>
                            <span class="filtertotal" style="display: ">(3)</span></a
                          >
                        </li>
                        <li class="dark-red">
                          <a href="#" value="Colour_Dark Red" style="display: " class=""
                            ><span>Dark Red</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="ecru">
                          <a href="#" value="Colour_Ecru" style="display: " class=""
                            ><span>Ecru</span>
                            <span class="filtertotal" style="display: ">(183)</span></a
                          >
                        </li>
                        <li class="gold">
                          <a href="#" value="Colour_Gold" style="display: " class=""
                            ><span>Gold</span>
                            <span class="filtertotal" style="display: ">(13)</span></a
                          >
                        </li>
                        <li class="green">
                          <a href="#" value="Colour_Green" style="display: " class=""
                            ><span>Green</span>
                            <span class="filtertotal" style="display: ">(325)</span></a
                          >
                        </li>
                        <li class="grey">
                          <a href="#" value="Colour_Grey" style="display: " class=""
                            ><span>Grey</span>
                            <span class="filtertotal" style="display: ">(111)</span></a
                          >
                        </li>
                        <li class="light-green">
                          <a href="#" value="Colour_Light Green" style="display: " class=""
                            ><span>Light Green</span>
                            <span class="filtertotal" style="display: ">(2)</span></a
                          >
                        </li>
                        <li class="light-red">
                          <a href="#" value="Colour_Light Red" style="display: " class=""
                            ><span>Light Red</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="maroon">
                          <a href="#" value="Colour_Maroon" style="display: " class=""
                            ><span>Maroon</span>
                            <span class="filtertotal" style="display: ">(30)</span></a
                          >
                        </li>
                        <li class="mauve">
                          <a href="#" value="Colour_Mauve" style="display: " class=""
                            ><span>Mauve</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="multicoloured">
                          <a
                            href="#"
                            value="Colour_Multicoloured"
                            style="display: "
                            class=""
                            ><span>Multicoloured</span>
                            <span class="filtertotal" style="display: ">(17)</span></a
                          >
                        </li>
                        <li class="navy">
                          <a href="#" value="Colour_Navy" style="display: " class=""
                            ><span>Navy</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="off-white">
                          <a href="#" value="Colour_Off-White" style="display: " class=""
                            ><span>Off-White</span>
                            <span class="filtertotal" style="display: ">(6)</span></a
                          >
                        </li>
                        <li class="orange">
                          <a href="#" value="Colour_Orange" style="display: " class=""
                            ><span>Orange</span>
                            <span class="filtertotal" style="display: ">(86)</span></a
                          >
                        </li>
                        <li class="peach">
                          <a href="#" value="Colour_Peach" style="display: " class=""
                            ><span>Peach</span>
                            <span class="filtertotal" style="display: ">(23)</span></a
                          >
                        </li>
                        <li class="pink">
                          <a href="#" value="Colour_Pink" style="display: " class=""
                            ><span>Pink</span>
                            <span class="filtertotal" style="display: ">(255)</span></a
                          >
                        </li>
                        <li class="purple">
                          <a href="#" value="Colour_Purple" style="display: " class=""
                            ><span>Purple</span>
                            <span class="filtertotal" style="display: ">(78)</span></a
                          >
                        </li>
                        <li class="red">
                          <a href="#" value="Colour_Red" style="display: " class=""
                            ><span>Red</span>
                            <span class="filtertotal" style="display: ">(160)</span></a
                          >
                        </li>
                        <li class="silver">
                          <a href="#" value="Colour_Silver" style="display: " class=""
                            ><span>Silver</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="teal">
                          <a href="#" value="Colour_Teal" style="display: " class=""
                            ><span>Teal</span>
                            <span class="filtertotal" style="display: ">(22)</span></a
                          >
                        </li>
                        <li class="white">
                          <a href="#" value="Colour_White" style="display: " class=""
                            ><span>White</span>
                            <span class="filtertotal" style="display: ">(121)</span></a
                          >
                        </li>
                        <li class="wine">
                          <a href="#" value="Colour_Wine" style="display: " class=""
                            ><span>Wine</span>
                            <span class="filtertotal" style="display: ">(3)</span></a
                          >
                        </li>
                        <li class="yellow">
                          <a href="#" value="Colour_Yellow" style="display: " class=""
                            ><span>Yellow</span>
                            <span class="filtertotal" style="display: ">(231)</span></a
                          >
                        </li>
                      </ul>

                    
                  </div>
                </div>
              </div>


              <div class="accordion-item">
                <h2 class="accordion-header" id="heading5">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse5" aria-expanded="false" aria-controls="collapse5">
                    Size
                  </button>
                </h2>
                <div id="collapse5" class="accordion-collapse collapse" aria-labelledby="heading5" data-bs-parent="#accordionExample">
                  <div class="accordion-body">

                    <ul class="list-unstyled" style="list-style-type: square">
                        <li class="XS">
                          <a href="#" value="Size_XS" style="display: " class=""
                            ><span>XS</span>
                            <span class="filtertotal" style="display: ">(242)</span></a
                          >
                        </li>
                        <li class="S">
                          <a href="#" value="Size_S" style="display: " class=""
                            ><span>S</span>
                            <span class="filtertotal" style="display: ">(243)</span></a
                          >
                        </li>
                        <li class="M">
                          <a href="#" value="Size_M" style="display: " class=""
                            ><span>M</span>
                            <span class="filtertotal" style="display: ">(243)</span></a
                          >
                        </li>
                        <li class="L">
                          <a href="#" value="Size_L" style="display: " class=""
                            ><span>L</span>
                            <span class="filtertotal" style="display: ">(243)</span></a
                          >
                        </li>
                        <li class="XL">
                          <a href="#" value="Size_XL" style="display: " class=""
                            ><span>XL</span>
                            <span class="filtertotal" style="display: ">(241)</span></a
                          >
                        </li>
                        <li class="XXL">
                          <a href="#" value="Size_XXL" style="display: " class=""
                            ><span>XXL</span>
                            <span class="filtertotal" style="display: ">(238)</span></a
                          >
                        </li>
                        <li class="6">
                          <a href="#" value="Size_6" style="display: " class=""
                            ><span>6</span>
                            <span class="filtertotal" style="display: ">(2147)</span></a
                          >
                        </li>
                        <li class="8">
                          <a href="#" value="Size_8" style="display: " class=""
                            ><span>8</span>
                            <span class="filtertotal" style="display: ">(2172)</span></a
                          >
                        </li>
                        <li class="10">
                          <a href="#" value="Size_10" style="display: " class=""
                            ><span>10</span>
                            <span class="filtertotal" style="display: ">(2170)</span></a
                          >
                        </li>
                        <li class="12">
                          <a href="#" value="Size_12" style="display: " class=""
                            ><span>12</span>
                            <span class="filtertotal" style="display: ">(2172)</span></a
                          >
                        </li>
                        <li class="14">
                          <a href="#" value="Size_14" style="display: " class=""
                            ><span>14</span>
                            <span class="filtertotal" style="display: ">(2171)</span></a
                          >
                        </li>
                        <li class="16">
                          <a href="#" value="Size_16" style="display: " class=""
                            ><span>16</span>
                            <span class="filtertotal" style="display: ">(2146)</span></a
                          >
                        </li>
                        <li class="18">
                          <a href="#" value="Size_18" style="display: " class=""
                            ><span>18</span>
                            <span class="filtertotal" style="display: ">(2143)</span></a
                          >
                        </li>
                        <li class="WS">
                          <a href="#" value="Size_WS" style="display: " class=""
                            ><span>WS</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="WM">
                          <a href="#" value="Size_WM" style="display: " class=""
                            ><span>WM</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="WL">
                          <a href="#" value="Size_WL" style="display: " class=""
                            ><span>WL</span>
                            <span class="filtertotal" style="display: ">(1)</span></a
                          >
                        </li>
                        <li class="20">
                          <a href="#" value="Size_20" style="display: " class=""
                            ><span>20</span>
                            <span class="filtertotal" style="display: ">(369)</span></a
                          >
                        </li>
                        <li class="22">
                          <a href="#" value="Size_22" style="display: " class=""
                            ><span>22</span>
                            <span class="filtertotal" style="display: ">(369)</span></a
                          >
                        </li>
                        <li class="2XL">
                          <a href="#" value="Size_2XL" style="display: " class=""
                            ><span>2XL</span>
                            <span class="filtertotal" style="display: ">(3)</span></a
                          >
                        </li>
                      </ul>


                </div>
              </div>
          </div>

          <div class="accordion-item">
            <h2 class="accordion-header" id="heading6">
              <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse6" aria-expanded="false" aria-controls="collapse6">
                Neck Type
              </button>
            </h2>
            <div id="collapse6" class="accordion-collapse collapse" aria-labelledby="heading6" data-bs-parent="#accordionExample">
              <div class="accordion-body">

                <ul class="list-unstyled" style="list-style-type: square">
                    <li class="boat-neck">
                      <a href="#" value="Neck Type_Boat Neck" style="display: " class=""
                        ><span>Boat Neck</span>
                        <span class="filtertotal" style="display: ">(62)</span></a
                      >
                    </li>
                    <li class="collared-v">
                      <a
                        href="#"
                        value="Neck Type_Collared-V"
                        style="display: "
                        class=""
                        ><span>Collared-V</span>
                        <span class="filtertotal" style="display: ">(5)</span></a
                      >
                    </li>
                    <li class="key-hole-neckline">
                      <a
                        href="#"
                        value="Neck Type_Key Hole Neckline"
                        style="display: "
                        class=""
                        ><span>Key Hole Neckline</span>
                        <span class="filtertotal" style="display: ">(4)</span></a
                      >
                    </li>
                    <li class="keyhole-neck">
                      <a
                        href="#"
                        value="Neck Type_Keyhole Neck"
                        style="display: "
                        class=""
                        ><span>Keyhole Neck</span>
                        <span class="filtertotal" style="display: ">(347)</span></a
                      >
                    </li>
                    <li class="lapel-collar">
                      <a
                        href="#"
                        value="Neck Type_Lapel Collar"
                        style="display: "
                        class=""
                        ><span>Lapel Collar</span>
                        <span class="filtertotal" style="display: ">(2)</span></a
                      >
                    </li>
                    <li class="mandarin-collar">
                      <a
                        href="#"
                        value="Neck Type_Mandarin Collar"
                        style="display: "
                        class=""
                        ><span>Mandarin Collar</span>
                        <span class="filtertotal" style="display: ">(735)</span></a
                      >
                    </li>
                    <li class="open-neck">
                      <a href="#" value="Neck Type_Open Neck" style="display: " class=""
                        ><span>Open Neck</span>
                        <span class="filtertotal" style="display: ">(1)</span></a
                      >
                    </li>
                    <li class="round-neck">
                      <a
                        href="#"
                        value="Neck Type_Round Neck"
                        style="display: "
                        class=""
                        ><span>Round Neck</span>
                        <span class="filtertotal" style="display: ">(1121)</span></a
                      >
                    </li>
                    <li class="shawl-collar">
                      <a
                        href="#"
                        value="Neck Type_Shawl Collar"
                        style="display: "
                        class=""
                        ><span>Shawl Collar</span>
                        <span class="filtertotal" style="display: ">(1)</span></a
                      >
                    </li>
                    <li class="shirt-collar">
                      <a
                        href="#"
                        value="Neck Type_Shirt Collar"
                        style="display: "
                        class=""
                        ><span>Shirt Collar</span>
                        <span class="filtertotal" style="display: ">(39)</span></a
                      >
                    </li>
                    <li class="square-neck">
                      <a
                        href="#"
                        value="Neck Type_Square Neck"
                        style="display: "
                        class=""
                        ><span>Square Neck</span>
                        <span class="filtertotal" style="display: ">(2)</span></a
                      >
                    </li>
                    <li class="v-neck">
                      <a href="#" value="Neck Type_V-Neck" style="display: " class=""
                        ><span>V-Neck</span>
                        <span class="filtertotal" style="display: ">(81)</span></a
                      >
                    </li>
                  </ul>
                

            </div>
          </div>
      </div>


      <div class="accordion-item">
        <h2 class="accordion-header" id="heading7">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse7" aria-expanded="false" aria-controls="collapse7">
            Sleeve
          </button>
        </h2>
        <div id="collapse7" class="accordion-collapse collapse" aria-labelledby="heading7" data-bs-parent="#accordionExample">
          <div class="accordion-body">

            <ul class="list-unstyled"  style="list-style-type: square"><li class="3_4-sleeve"><a href="#" value="Sleeve_3/4 Sleeve" style="display:;" class=""><span>3/4 Sleeve</span> <span class="filtertotal" style="display:;">(2043)</span></a></li><li class="elbow-sleeve"><a href="#" value="Sleeve_Elbow Sleeve" style="display:;" class=""><span>Elbow Sleeve</span> <span class="filtertotal" style="display:;">(16)</span></a></li><li class="full-sleeve"><a href="#" value="Sleeve_Full Sleeve" style="display:;" class=""><span>Full Sleeve</span> <span class="filtertotal" style="display:;">(285)</span></a></li><li class="half-sleeve"><a href="#" value="Sleeve_Half Sleeve" style="display:;" class=""><span>Half Sleeve</span> <span class="filtertotal" style="display:;">(22)</span></a></li><li class="kaftan-sleeve"><a href="#" value="Sleeve_Kaftan Sleeve" style="display:;" class=""><span>Kaftan Sleeve</span> <span class="filtertotal" style="display:;">(2)</span></a></li><li class="short-sleeve"><a href="#" value="Sleeve_Short Sleeve" style="display:;" class=""><span>Short Sleeve</span> <span class="filtertotal" style="display:;">(58)</span></a></li><li class="sleeveless"><a href="#" value="Sleeve_Sleeveless" style="display:;" class=""><span>Sleeveless</span> <span class="filtertotal" style="display:;">(54)</span></a></li></ul>
            

        </div>
      </div>
  </div>




  <div class="accordion-item">
    <h2 class="accordion-header" id="heading8">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse8" aria-expanded="false" aria-controls="collapse8">
        Occasion
      </button>
    </h2>
    <div id="collapse8" class="accordion-collapse collapse" aria-labelledby="heading8" data-bs-parent="#accordionExample">
      <div class="accordion-body">
 
<ul class="list-unstyled"  style="list-style-type: square"><li class="casual"><a href="#" value="Occasion_Casual" style="display:;" class=""><span>Casual</span> <span class="filtertotal" style="display:;">(1169)</span></a></li><li class="fashion"><a href="#" value="Occasion_Fashion" style="display:;" class=""><span>Fashion</span> <span class="filtertotal" style="display:;">(6)</span></a></li><li class="festive"><a href="#" value="Occasion_Festive" style="display:;" class=""><span>Festive</span> <span class="filtertotal" style="display:;">(915)</span></a></li></ul>
        

    </div>
  </div>
</div>



<div class="accordion-item">
    <h2 class="accordion-header" id="heading9">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse9" aria-expanded="false" aria-controls="collapse9">
        Length
      </button>
    </h2>
    <div id="collapse9" class="accordion-collapse collapse" aria-labelledby="heading9" data-bs-parent="#accordionExample">
      <div class="accordion-body">
 
        <ul class="list-unstyled"  style="list-style-type: square">
            <li class="above-knee">
              <a href="#" value="Length_Above Knee" style="display: " class=""
                ><span>Above Knee</span>
                <span class="filtertotal" style="display: ">(86)</span></a
              >
            </li>
            <li class="ankle-length">
              <a href="#" value="Length_Ankle Length" style="display: " class=""
                ><span>Ankle Length</span>
                <span class="filtertotal" style="display: ">(63)</span></a
              >
            </li>
            <li class="calf-length">
              <a href="#" value="Length_Calf Length" style="display: " class=""
                ><span>Calf Length</span>
                <span class="filtertotal" style="display: ">(1355)</span></a
              >
            </li>
            <li class="knee-length">
              <a href="#" value="Length_Knee Length" style="display: " class=""
                ><span>Knee Length</span>
                <span class="filtertotal" style="display: ">(539)</span></a
              >
            </li>
          </ul>

        

    </div>
  </div>
</div>

<div class="accordion-item">
    <h2 class="accordion-header" id="heading10">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse10" aria-expanded="false" aria-controls="collapse10">
        Fastening/Closure
      </button>
    </h2>
    <div id="collapse10" class="accordion-collapse collapse" aria-labelledby="heading10" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <ul class="list-unstyled" style="list-style-type: square"><li class="print"><a href="#" value="Fastening/Closure_Print" style="display:;" class=""><span>Print</span> <span class="filtertotal" style="display:;">(14)</span></a></li><li class="solid"><a href="#" value="Fastening/Closure_Solid" style="display:;" class=""><span>Solid</span> <span class="filtertotal" style="display:;">(6)</span></a></li><li class="yd--dobby"><a href="#" value="Fastening/Closure_Yd- Dobby" style="display:;" class=""><span>Yd- Dobby</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="yd--jacquard"><a href="#" value="Fastening/Closure_Yd- Jacquard" style="display:;" class=""><span>Yd- Jacquard</span> <span class="filtertotal" style="display:;">(2)</span></a></li></ul>

        

    </div>
  </div>
</div>


<div class="accordion-item">
    <h2 class="accordion-header" id="heading11">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse11" aria-expanded="false" aria-controls="collapse11">
        Pattern
      </button>
    </h2>
    <div id="collapse11" class="accordion-collapse collapse" aria-labelledby="heading11" data-bs-parent="#accordionExample">
      <div class="accordion-body">
<ul class="list-unstyled" style="list-style-type: square"><li class="abstract"><a href="#" value="Pattern_Abstract" style="display:;" class=""><span>Abstract</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="ajrakh-print"><a href="#" value="Pattern_Ajrakh Print" style="display:;" class=""><span>Ajrakh Print</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="all-over-buti"><a href="#" value="Pattern_All Over Buti" style="display:;" class=""><span>All Over Buti</span> <span class="filtertotal" style="display:;">(42)</span></a></li><li class="all-over-jaal"><a href="#" value="Pattern_All Over Jaal" style="display:;" class=""><span>All Over Jaal</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="animal"><a href="#" value="Pattern_Animal" style="display:;" class=""><span>Animal</span> <span class="filtertotal" style="display:;">(11)</span></a></li><li class="aztec_tribal"><a href="#" value="Pattern_Aztec/Tribal" style="display:;" class=""><span>Aztec/Tribal</span> <span class="filtertotal" style="display:;">(2)</span></a></li><li class="bandhej"><a href="#" value="Pattern_Bandhej" style="display:;" class=""><span>Bandhej</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="block-print"><a href="#" value="Pattern_Block Print" style="display:;" class=""><span>Block Print</span> <span class="filtertotal" style="display:;">(22)</span></a></li><li class="checkered"><a href="#" value="Pattern_Checkered" style="display:;" class=""><span>Checkered</span> <span class="filtertotal" style="display:;">(16)</span></a></li><li class="embellished"><a href="#" value="Pattern_Embellished" style="display:;" class=""><span>Embellished</span> <span class="filtertotal" style="display:;">(14)</span></a></li><li class="embroidered"><a href="#" value="Pattern_Embroidered" style="display:;" class=""><span>Embroidered</span> <span class="filtertotal" style="display:;">(5)</span></a></li><li class="floral"><a href="#" value="Pattern_Floral" style="display:;" class=""><span>Floral</span> <span class="filtertotal" style="display:;">(634)</span></a></li><li class="geometric"><a href="#" value="Pattern_Geometric" style="display:;" class=""><span>Geometric</span> <span class="filtertotal" style="display:;">(434)</span></a></li><li class="ikkat"><a href="#" value="Pattern_Ikkat" style="display:;" class=""><span>Ikkat</span> <span class="filtertotal" style="display:;">(8)</span></a></li><li class="ornamental"><a href="#" value="Pattern_Ornamental" style="display:;" class=""><span>Ornamental</span> <span class="filtertotal" style="display:;">(6)</span></a></li><li class="paisley"><a href="#" value="Pattern_Paisley" style="display:;" class=""><span>Paisley</span> <span class="filtertotal" style="display:;">(69)</span></a></li><li class="polka-dots"><a href="#" value="Pattern_Polka Dots" style="display:;" class=""><span>Polka Dots</span> <span class="filtertotal" style="display:;">(48)</span></a></li><li class="printed"><a href="#" value="Pattern_Printed" style="display:;" class=""><span>Printed</span> <span class="filtertotal" style="display:;">(351)</span></a></li><li class="shibori"><a href="#" value="Pattern_Shibori" style="display:;" class=""><span>Shibori</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="solid"><a href="#" value="Pattern_Solid" style="display:;" class=""><span>Solid</span> <span class="filtertotal" style="display:;">(593)</span></a></li><li class="striped"><a href="#" value="Pattern_Striped" style="display:;" class=""><span>Striped</span> <span class="filtertotal" style="display:;">(121)</span></a></li><li class="tribal"><a href="#" value="Pattern_Tribal" style="display:;" class=""><span>Tribal</span> <span class="filtertotal" style="display:;">(38)</span></a></li><li class="tropical"><a href="#" value="Pattern_Tropical" style="display:;" class=""><span>Tropical</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="woven-design"><a href="#" value="Pattern_Woven Design" style="display:;" class=""><span>Woven Design</span> <span class="filtertotal" style="display:;">(2)</span></a></li></ul>

        

    </div>
  </div>
</div>

<div class="accordion-item">
    <h2 class="accordion-header" id="heading12">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse12" aria-expanded="false" aria-controls="collapse12">
        Ornamentation
      </button>
    </h2>
    <div id="collapse12" class="accordion-collapse collapse" aria-labelledby="heading12" data-bs-parent="#accordionExample">
      <div class="accordion-body">

<ul class="list-unstyled" style="list-style-type: square"><li class="beads"><a href="#" value="Ornamentation_Beads" style="display:;" class=""><span>Beads</span> <span class="filtertotal" style="display:;">(5)</span></a></li><li class="beads-and-stones"><a href="#" value="Ornamentation_Beads and Stones" style="display:;" class=""><span>Beads and Stones</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="dori-embroidery"><a href="#" value="Ornamentation_Dori Embroidery" style="display:;" class=""><span>Dori Embroidery</span> <span class="filtertotal" style="display:;">(9)</span></a></li><li class="gotta-patti"><a href="#" value="Ornamentation_Gotta Patti" style="display:;" class=""><span>Gotta Patti</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="metallic-dori-embroidery"><a href="#" value="Ornamentation_Metallic Dori Embroidery" style="display:;" class=""><span>Metallic Dori Embroidery</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="metallic-embroidery"><a href="#" value="Ornamentation_Metallic Embroidery" style="display:;" class=""><span>Metallic Embroidery</span> <span class="filtertotal" style="display:;">(30)</span></a></li><li class="sequins"><a href="#" value="Ornamentation_Sequins" style="display:;" class=""><span>Sequins</span> <span class="filtertotal" style="display:;">(28)</span></a></li><li class="shells"><a href="#" value="Ornamentation_Shells" style="display:;" class=""><span>Shells</span> <span class="filtertotal" style="display:;">(2)</span></a></li><li class="thread-embroidery"><a href="#" value="Ornamentation_Thread Embroidery" style="display:;" class=""><span>Thread Embroidery</span> <span class="filtertotal" style="display:;">(102)</span></a></li><li class="thread-work"><a href="#" value="Ornamentation_Thread Work" style="display:;" class=""><span>Thread Work</span> <span class="filtertotal" style="display:;">(28)</span></a></li></ul>
        

    </div>
  </div>
</div>

<div class="accordion-item">
    <h2 class="accordion-header" id="heading13">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse13" aria-expanded="false" aria-controls="collapse13">
        Fabric Family
      </button>
    </h2>
    <div id="collapse13" class="accordion-collapse collapse" aria-labelledby="heading13" data-bs-parent="#accordionExample">
      <div class="accordion-body">

<ul class="list-unstyled" style="list-style-type: square"><li class="100_-man-made-fiber"><a href="#" value="Fabric Family_100% Man Made Fiber" style="display:;" class=""><span>100% Man Made Fiber</span> <span class="filtertotal" style="display:;">(194)</span></a></li><li class="30_s-2-way-slub"><a href="#" value="Fabric Family_30'S 2 Way Slub" style="display:;" class=""><span>30'S 2 Way Slub</span> <span class="filtertotal" style="display:none;">(0)</span></a></li><li class="30_s-rayon"><a href="#" value="Fabric Family_30'S Rayon" style="display:;" class=""><span>30'S Rayon</span> <span class="filtertotal" style="display:none;">(0)</span></a></li><li class="60_s-cambric"><a href="#" value="Fabric Family_60'S Cambric" style="display:;" class=""><span>60'S Cambric</span> <span class="filtertotal" style="display:none;">(0)</span></a></li><li class="92x80-voile"><a href="#" value="Fabric Family_92X80 Voile" style="display:;" class=""><span>92X80 Voile</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="acrylic"><a href="#" value="Fabric Family_Acrylic" style="display:;" class=""><span>Acrylic</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="brasso"><a href="#" value="Fabric Family_Brasso" style="display:;" class=""><span>Brasso</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="cambric"><a href="#" value="Fabric Family_Cambric" style="display:;" class=""><span>Cambric</span> <span class="filtertotal" style="display:;">(47)</span></a></li><li class="chambray"><a href="#" value="Fabric Family_Chambray" style="display:;" class=""><span>Chambray</span> <span class="filtertotal" style="display:;">(2)</span></a></li><li class="chanderi"><a href="#" value="Fabric Family_Chanderi" style="display:;" class=""><span>Chanderi</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="cotton"><a href="#" value="Fabric Family_Cotton" style="display:;" class=""><span>Cotton</span> <span class="filtertotal" style="display:;">(371)</span></a></li><li class="cotton-blend"><a href="#" value="Fabric Family_Cotton Blend" style="display:;" class=""><span>Cotton Blend</span> <span class="filtertotal" style="display:;">(107)</span></a></li><li class="cotton-flax"><a href="#" value="Fabric Family_Cotton Flax" style="display:;" class=""><span>Cotton Flax</span> <span class="filtertotal" style="display:;">(17)</span></a></li><li class="crepe"><a href="#" value="Fabric Family_Crepe" style="display:;" class=""><span>Crepe</span> <span class="filtertotal" style="display:;">(36)</span></a></li><li class="denim"><a href="#" value="Fabric Family_Denim" style="display:;" class=""><span>Denim</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="dobbey"><a href="#" value="Fabric Family_Dobbey" style="display:;" class=""><span>Dobbey</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="dobby"><a href="#" value="Fabric Family_Dobby" style="display:;" class=""><span>Dobby</span> <span class="filtertotal" style="display:;">(48)</span></a></li><li class="flax"><a href="#" value="Fabric Family_Flax" style="display:;" class=""><span>Flax</span> <span class="filtertotal" style="display:;">(91)</span></a></li><li class="georgette"><a href="#" value="Fabric Family_Georgette" style="display:;" class=""><span>Georgette</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="jacquard"><a href="#" value="Fabric Family_Jacquard" style="display:;" class=""><span>Jacquard</span> <span class="filtertotal" style="display:;">(9)</span></a></li><li class="kota"><a href="#" value="Fabric Family_Kota" style="display:;" class=""><span>Kota</span> <span class="filtertotal" style="display:;">(4)</span></a></li><li class="linen"><a href="#" value="Fabric Family_Linen" style="display:;" class=""><span>Linen</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="liva"><a href="#" value="Fabric Family_Liva" style="display:;" class=""><span>Liva</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="misdent"><a href="#" value="Fabric Family_Misdent" style="display:;" class=""><span>Misdent</span> <span class="filtertotal" style="display:;">(2)</span></a></li><li class="natural-cotton-flax"><a href="#" value="Fabric Family_Natural Cotton Flax" style="display:;" class=""><span>Natural Cotton Flax</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="net"><a href="#" value="Fabric Family_Net" style="display:;" class=""><span>Net</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="nylon"><a href="#" value="Fabric Family_Nylon" style="display:;" class=""><span>Nylon</span> <span class="filtertotal" style="display:;">(2)</span></a></li><li class="polyester"><a href="#" value="Fabric Family_Polyester" style="display:;" class=""><span>Polyester</span> <span class="filtertotal" style="display:;">(65)</span></a></li><li class="ps"><a href="#" value="Fabric Family_Ps" style="display:;" class=""><span>Ps</span> <span class="filtertotal" style="display:;">(9)</span></a></li><li class="ps-slub"><a href="#" value="Fabric Family_Ps Slub" style="display:;" class=""><span>Ps Slub</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="rayon"><a href="#" value="Fabric Family_Rayon" style="display:;" class=""><span>Rayon</span> <span class="filtertotal" style="display:;">(184)</span></a></li><li class="rayon-flax"><a href="#" value="Fabric Family_Rayon Flax" style="display:;" class=""><span>Rayon Flax</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="shantung"><a href="#" value="Fabric Family_Shantung" style="display:;" class=""><span>Shantung</span> <span class="filtertotal" style="display:;">(101)</span></a></li><li class="silk"><a href="#" value="Fabric Family_Silk" style="display:;" class=""><span>Silk</span> <span class="filtertotal" style="display:;">(9)</span></a></li><li class="slub"><a href="#" value="Fabric Family_Slub" style="display:;" class=""><span>Slub</span> <span class="filtertotal" style="display:;">(12)</span></a></li><li class="viscose"><a href="#" value="Fabric Family_Viscose" style="display:;" class=""><span>Viscose</span> <span class="filtertotal" style="display:;">(589)</span></a></li><li class="viscose-blend"><a href="#" value="Fabric Family_Viscose Blend" style="display:;" class=""><span>Viscose Blend</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="voile"><a href="#" value="Fabric Family_Voile" style="display:;" class=""><span>Voile</span> <span class="filtertotal" style="display:;">(10)</span></a></li></ul>
        

    </div>
  </div>
</div>

<div class="accordion-item">
    <h2 class="accordion-header" id="heading14">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapse14" aria-expanded="false" aria-controls="collapse14">
        Closure
      </button>
    </h2>
    <div id="collapse14" class="accordion-collapse collapse" aria-labelledby="heading14" data-bs-parent="#accordionExample">
      <div class="accordion-body">

<ul class="list-unstyled" style="list-style-type: square"><li class="button"><a href="#" value="Closure_Button" style="display:;" class=""><span>Button</span> <span class="filtertotal" style="display:;">(500)</span></a></li><li class="button-_-key-hole"><a href="#" value="Closure_Button &amp; Key Hole" style="display:;" class=""><span>Button &amp; Key Hole</span> <span class="filtertotal" style="display:;">(37)</span></a></li><li class="button-_-keyhole"><a href="#" value="Closure_Button &amp; Keyhole" style="display:;" class=""><span>Button &amp; Keyhole</span> <span class="filtertotal" style="display:;">(58)</span></a></li><li class="button-fly"><a href="#" value="Closure_Button Fly" style="display:;" class=""><span>Button Fly</span> <span class="filtertotal" style="display:;">(2)</span></a></li><li class="buttons"><a href="#" value="Closure_Buttons" style="display:;" class=""><span>Buttons</span> <span class="filtertotal" style="display:;">(259)</span></a></li><li class="dori-_-tassel"><a href="#" value="Closure_Dori &amp; Tassel" style="display:;" class=""><span>Dori &amp; Tassel</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="dori-tie-ups"><a href="#" value="Closure_Dori Tie Ups" style="display:;" class=""><span>Dori Tie Ups</span> <span class="filtertotal" style="display:;">(14)</span></a></li><li class="hook-_-eye"><a href="#" value="Closure_Hook &amp; Eye" style="display:;" class=""><span>Hook &amp; Eye</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="hook-fly"><a href="#" value="Closure_Hook Fly" style="display:;" class=""><span>Hook Fly</span> <span class="filtertotal" style="display:;">(5)</span></a></li><li class="hooks-fly"><a href="#" value="Closure_Hooks Fly" style="display:;" class=""><span>Hooks Fly</span> <span class="filtertotal" style="display:;">(3)</span></a></li><li class="side-zip"><a href="#" value="Closure_Side Zip" style="display:;" class=""><span>Side Zip</span> <span class="filtertotal" style="display:;">(1)</span></a></li><li class="slip-on"><a href="#" value="Closure_Slip On" style="display:;" class=""><span>Slip On</span> <span class="filtertotal" style="display:;">(54)</span></a></li><li class="slip-on"><a href="#" value="Closure_Slip-on" style="display:;" class=""><span>Slip-on</span> <span class="filtertotal" style="display:;">(93)</span></a></li><li class="straight"><a href="#" value="Closure_Straight" style="display:;" class=""><span>Straight</span> <span class="filtertotal" style="display:;">(4)</span></a></li><li class="tie-up"><a href="#" value="Closure_Tie-up" style="display:;" class=""><span>Tie-up</span> <span class="filtertotal" style="display:;">(1)</span></a></li></ul>
        

    </div>
  </div>
</div>



        </div>


    </div>

    <div class="col mt-5">
        



        <div class="col-md-12 product-list"><div class="row"><div class="col-md-12"><div class="error_message" style="display:none;"></div></div> <div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-fern-green-a-line-printed-kurta-22few17326-118119.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-fern-green-a-line-printed-kurta-22few17326-118119.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17326-118119/300/22FEW17326-118119_1.JPG" alt="Fern Green A-line Printed Kurta" title="Fern Green A-line Printed Kurta" data-v-62a35744=""></div></a> <!---->  <!----></div> <p data-v-62a35744=""><a href="/product-fern-green-a-line-printed-kurta-22few17326-118119.html" data-v-62a35744="" class="">Fern Green A-line Printed Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2599</span> <span class="price" data-v-62a35744="">Rs. 2599</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2599</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-smoke-grey-a-line-kurta-22few17277-116731.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-smoke-grey-a-line-kurta-22few17277-116731.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17277-116731/300/22FEW17277-116731_1.JPG" alt="Smoke Grey A-line Kurta" title="Smoke Grey A-line Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-smoke-grey-a-line-kurta-22few17277-116731.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-smoke-grey-a-line-kurta-22few17277-116731.html" data-v-62a35744="" class="">Smoke Grey A-line Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2399</span> <span class="price" data-v-62a35744="">Rs. 2399</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2399</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-tuscany-pink-a-line-kurta-22few17276-116746.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-tuscany-pink-a-line-kurta-22few17276-116746.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17276-116746/300/22FEW17276-116746_1.JPG" alt="Tuscany Pink A-line Kurta" title="Tuscany Pink A-line Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-tuscany-pink-a-line-kurta-22few17276-116746.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-tuscany-pink-a-line-kurta-22few17276-116746.html" data-v-62a35744="" class="">Tuscany Pink A-line Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2799</span> <span class="price" data-v-62a35744="">Rs. 2799</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2799</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-grey-printed-a-line-kurta-22few17522-117456.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-grey-printed-a-line-kurta-22few17522-117456.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17522-117456/300/22FEW17522-117456_1.JPG" alt="Grey Printed A-Line Kurta" title="Grey Printed A-Line Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-grey-printed-a-line-kurta-22few17522-117456.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-grey-printed-a-line-kurta-22few17522-117456.html" data-v-62a35744="" class="">Grey Printed A-Line Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2999</span> <span class="price" data-v-62a35744="">Rs. 2999</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2999</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-beige-stripe-print-kurta-22few17274-116735.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-beige-stripe-print-kurta-22few17274-116735.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17274-116735/300/22FEW17274-116735_1.JPG" alt="Beige Stripe Print Kurta" title="Beige Stripe Print Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-beige-stripe-print-kurta-22few17274-116735.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-beige-stripe-print-kurta-22few17274-116735.html" data-v-62a35744="" class="">Beige Stripe Print Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2399</span> <span class="price" data-v-62a35744="">Rs. 2399</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2399</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-sage-green-jacquard-kurta-with-embroidery-21auw14029-311668.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-sage-green-jacquard-kurta-with-embroidery-21auw14029-311668.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/21AUW14029-311668/300/21AUW14029-311668_1.JPG" alt="Sage Green Jacquard Kurta with Embroidery" title="Sage Green Jacquard Kurta with Embroidery" data-v-62a35744=""></div></a> <!----> <!----> <!----></div> <p data-v-62a35744=""><a href="/product-sage-green-jacquard-kurta-with-embroidery-21auw14029-311668.html" data-v-62a35744="" class="">Sage Green Jacquard Kurta with Embroidery</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2999</span> <span class="price" data-v-62a35744="">Rs. 2999</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2999</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-rosedust-pink-printed-kurta-22few17272-116763.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-rosedust-pink-printed-kurta-22few17272-116763.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17272-116763/300/22FEW17272-116763_1.JPG" alt="Rosedust Pink Printed Kurta" title="Rosedust Pink Printed Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-rosedust-pink-printed-kurta-22few17272-116763.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-rosedust-pink-printed-kurta-22few17272-116763.html" data-v-62a35744="" class="">Rosedust Pink Printed Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2399</span> <span class="price" data-v-62a35744="">Rs. 2399</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2399</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-light-blue-cotton-dobby-straight-kurta-22few17585-312195.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-light-blue-cotton-dobby-straight-kurta-22few17585-312195.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17585-312195/300/22FEW17585-312195_1.JPG" alt="Light Blue Cotton Dobby Straight Kurta" title="Light Blue Cotton Dobby Straight Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-light-blue-cotton-dobby-straight-kurta-22few17585-312195.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-light-blue-cotton-dobby-straight-kurta-22few17585-312195.html" data-v-62a35744="" class="">Light Blue Cotton Dobby Straight Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 1999</span> <span class="price" data-v-62a35744="">Rs. 1999</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 1999</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-brown-a-line-printed-kurta-22few17280-116749.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-brown-a-line-printed-kurta-22few17280-116749.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17280-116749/300/22FEW17280-116749_1.JPG" alt="Brown A-Line Printed Kurta" title="Brown A-Line Printed Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-brown-a-line-printed-kurta-22few17280-116749.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-brown-a-line-printed-kurta-22few17280-116749.html" data-v-62a35744="" class="">Brown A-Line Printed Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2599</span> <span class="price" data-v-62a35744="">Rs. 2599</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2599</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-deep-teal-floral-pleated-kurta-in-round-neck-22few17472-117945.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-deep-teal-floral-pleated-kurta-in-round-neck-22few17472-117945.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17472-117945/300/22FEW17472-117945_1.JPG" alt="Deep Teal Floral Pleated Kurta In Round Neck" title="Deep Teal Floral Pleated Kurta In Round Neck" data-v-62a35744=""></div></a> <!----> <a href="/product-deep-teal-floral-pleated-kurta-in-round-neck-22few17472-117945.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-deep-teal-floral-pleated-kurta-in-round-neck-22few17472-117945.html" data-v-62a35744="" class="">Deep Teal Floral Pleated Kurta In Round Neck</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2399</span> <span class="price" data-v-62a35744="">Rs. 2399</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2399</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-mint-blue-a-line-kurta-21few13510l-114183.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-mint-blue-a-line-kurta-21few13510l-114183.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/21FEW13510L-114183/300/20FEW13510L-114183_1.JPG" alt="Mint Blue A-line Kurta" title="Mint Blue A-line Kurta" data-v-62a35744=""></div></a> <!----> <!----> <!----></div> <p data-v-62a35744=""><a href="/product-mint-blue-a-line-kurta-21few13510l-114183.html" data-v-62a35744="" class="">Mint Blue A-line Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 1899</span> <span class="price" data-v-62a35744="">Rs. 1899</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 1899</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-royal-blue-pleated-kurta-with-embroidery-21auw16112-215858.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-royal-blue-pleated-kurta-with-embroidery-21auw16112-215858.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/21AUW16112-215858/300/21AUW16112-215858_1.JPG" alt="Royal Blue Pleated Kurta with Embroidery" title="Royal Blue Pleated Kurta with Embroidery" data-v-62a35744=""></div></a> <!----> <!----> <!----></div> <p data-v-62a35744=""><a href="/product-royal-blue-pleated-kurta-with-embroidery-21auw16112-215858.html" data-v-62a35744="" class="">Royal Blue Pleated Kurta with Embroidery</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 1999</span> <span class="price" data-v-62a35744="">Rs. 1999</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 1999</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-yellow-embroidered-a-line-kurta-20few13493-213696.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-yellow-embroidered-a-line-kurta-20few13493-213696.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/20FEW13493-213696/300/20FEW13493-213696_1.JPG" alt="Yellow Embroidered A-Line Kurta" title="Yellow Embroidered A-Line Kurta" data-v-62a35744=""></div></a> <!----> <!----> <!----></div> <p data-v-62a35744=""><a href="/product-yellow-embroidered-a-line-kurta-20few13493-213696.html" data-v-62a35744="" class="">Yellow Embroidered A-Line Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2799</span> <span class="price" data-v-62a35744="">Rs. 2799</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2799</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-black-solid-festive-kurta-with-metallic-embroidery-21skw14766-65626.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-black-solid-festive-kurta-with-metallic-embroidery-21skw14766-65626.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/21SKW14766-65626/300/21SKW14766-65626_1.JPG" alt="Black Solid Festive kurta with Metallic Embroidery" title="Black Solid Festive kurta with Metallic Embroidery" data-v-62a35744=""></div></a> <!----> <!----> <!----></div> <p data-v-62a35744=""><a href="/product-black-solid-festive-kurta-with-metallic-embroidery-21skw14766-65626.html" data-v-62a35744="" class="">Black Solid Festive kurta with Metallic Embroidery</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 1799</span> <span class="price" data-v-62a35744="">Rs. 1799</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 1799</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-purple-printed-kurta-22fes10739-118381.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-purple-printed-kurta-22fes10739-118381.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FES10739-118381/300/22FES10739-118381_1.JPG" alt="Purple Printed Kurta" title="Purple Printed Kurta" data-v-62a35744=""></div></a> <!----> <!----> <!----></div> <p data-v-62a35744=""><a href="/product-purple-printed-kurta-22fes10739-118381.html" data-v-62a35744="" class="">Purple Printed Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2799</span> <span class="price" data-v-62a35744="">Rs. 2799</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2799</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-cobalt-blue-embroidered-kurta-22few17331-215902.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-cobalt-blue-embroidered-kurta-22few17331-215902.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17331-215902/300/22FEW17331-215902_1.JPG" alt="Cobalt Blue Embroidered Kurta" title="Cobalt Blue Embroidered Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-cobalt-blue-embroidered-kurta-22few17331-215902.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-cobalt-blue-embroidered-kurta-22few17331-215902.html" data-v-62a35744="" class="">Cobalt Blue Embroidered Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 1999</span> <span class="price" data-v-62a35744="">Rs. 1999</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 1999</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-light-teal-floral-print-kurta-in-keyhole-neckline-21skw16014-50547.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-light-teal-floral-print-kurta-in-keyhole-neckline-21skw16014-50547.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/21SKW16014-50547/300/21SKW16014-50547_1.JPG" alt="Light Teal Floral Print Kurta in Keyhole Neckline" title="Light Teal Floral Print Kurta in Keyhole Neckline" data-v-62a35744=""></div></a> <!----> <!----> <!----></div> <p data-v-62a35744=""><a href="/product-light-teal-floral-print-kurta-in-keyhole-neckline-21skw16014-50547.html" data-v-62a35744="" class="">Light Teal Floral Print Kurta in Keyhole Neckline</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 1699</span> <span class="price" data-v-62a35744="">Rs. 1699</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 1699</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-orange-rust-and-ecru-printed-a-line-kurta-22few17317-118121.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-orange-rust-and-ecru-printed-a-line-kurta-22few17317-118121.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17317-118121/300/22FEW17317-118121.JPG" alt="Orange Rust and Ecru Printed A-line Kurta" title="Orange Rust and Ecru Printed A-line Kurta" data-v-62a35744=""></div></a> <!----> <a href="/product-orange-rust-and-ecru-printed-a-line-kurta-22few17317-118121.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-orange-rust-and-ecru-printed-a-line-kurta-22few17317-118121.html" data-v-62a35744="" class="">Orange Rust and Ecru Printed A-line Kurta</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 1999</span> <span class="price" data-v-62a35744="">Rs. 1999</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 1999</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-light-green-dobby-straight-kurta-22few17458-312208.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-light-green-dobby-straight-kurta-22few17458-312208.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW17458-312208/300/22FEW17458-312208_1.JPG" alt="Light Green Dobby Straight Kurta " title="Light Green Dobby Straight Kurta " data-v-62a35744=""></div></a> <!----> <a href="/product-light-green-dobby-straight-kurta-22few17458-312208.html" class="hopeistrending" data-v-62a35744=""></a> <!----></div> <p data-v-62a35744=""><a href="/product-light-green-dobby-straight-kurta-22few17458-312208.html" data-v-62a35744="" class="">Light Green Dobby Straight Kurta </a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 1899</span> <span class="price" data-v-62a35744="">Rs. 1899</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 1899</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div><div class="col-md-3 col-sm-6 col-xs-6 col-6"><div class="slide-box" data-v-62a35744=""><!----> <!----> <div class="product-box" data-v-62a35744=""><!----> <a href="/product-ecru-printed-kurta-with-embroidery-22few14787-116329.html" class="view-detail" data-v-62a35744="">
            View Detail
          </a> <a href="/product-ecru-printed-kurta-with-embroidery-22few14787-116329.html" data-v-62a35744="" class=""><div class="w-100 min-height-pdp" data-v-62a35744=""><!----> <img src="https://wforwoman.gumlet.io/product/22FEW14787-116329/300/22FEW14787-116329_1.JPG" alt="Ecru Printed Kurta with Embroidery" title="Ecru Printed Kurta with Embroidery" data-v-62a35744=""></div></a> <!----> <!----> <!----></div> <p data-v-62a35744=""><a href="/product-ecru-printed-kurta-with-embroidery-22few14787-116329.html" data-v-62a35744="" class="">Ecru Printed Kurta with Embroidery</a></p> <div class="price" style="display:none;" data-v-62a35744=""><p data-v-62a35744=""><span class="old-price" data-v-62a35744="">Rs. 2599</span> <span class="price" data-v-62a35744="">Rs. 2599</span> <span class="discount_percent font-bold" style="display:;" data-v-62a35744="">
              -
              0%
            </span></p></div> <div class="price" style="display:;" data-v-62a35744=""><p data-v-62a35744=""><span class="price" data-v-62a35744="">Rs. 2599</span></p></div> <div class="size" style="display:;" data-v-62a35744=""><p data-v-62a35744="">
            Size -
            <span data-v-62a35744="">6</span><span data-v-62a35744="">8</span><span data-v-62a35744="">10</span><span data-v-62a35744="">12</span><span data-v-62a35744="">14</span><span data-v-62a35744="">16</span><span data-v-62a35744="">18</span><span data-v-62a35744="">20</span><span data-v-62a35744="">22</span></p></div></div></div></div> <div class="product_loader" style="display:;"><img src="/images/giphy.gif"></div></div>






    </div>


</div>

          </div>
    </div>
</template>
<script>


export default{
    name:'ShopingHome',
    
}
</script>
<style scoped>
.product-list .slide-box {
    border: 1px solid #fff;
    padding-bottom: 10px;
    margin: 15px 0;
    position: relative;
}
.product-section-main .product-list .product-box {
    position: relative;
    overflow: hidden;
}
.product-list .slide-box .size {
    opacity: 0;
    transition: all .5s;
}
body.w-store .product-section-main .product-list .product-box .view-detail {
    background: #c11d14;
    z-index: 99;
}
.product-section-main .product-list .slide-box:hover .view-detail {
    opacity: 1;
    bottom: 0;
}
.product-section-main .product-list .product-box .view-detail, .wordrobe-product .product-list .wordrobe-content .view-detail {
    color: #fff;
    font-size: 13px;
    line-height: 38px;
    width: 100%;
    text-align: center;
    text-transform: uppercase;
    text-decoration: none;
    transition: all .5s;
}

.product-section-main .product-list .product-box .view-detail {
    position: absolute;
    bottom: -58px;
    opacity: 0;
}
*, :after, :before {
    box-sizing: border-box;
}
a, button {
    outline: none!important;
    text-decoration: none;
}

</style>