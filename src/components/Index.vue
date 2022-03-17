<template>
  <div class="container">
      <section ref="content">
      <section>
      <h1>VISUAL VECHILE INSPECTION REPORT</h1>
      <hr>
      <div class="head">
        <h3>Dealer Name: <span></span> </h3>
        <h3>Technician: </h3>
        <h3>Date: </h3>
      </div>
      <div class="head">
        <h3>Customer Name: </h3>
        <h3>Yr./Make/Model: </h3>
        <h3>Hat/Tag#: </h3>
      </div>
      <div class="head">
        <h3>Mileage: </h3>
        <h3>VIN: </h3>
        <h3>Repair Order: </h3>
      </div>
    </section>
    <section class="table">
      <div class="tab1">
          <div>
            <div class="green-head">CHECKED AND OKAY</div>
            <div class="yellow-head ">MAY NEED FUTURE ATTENTION</div>
            <div class="red-head">REQUIRES IMMEDIATE ATTENTION</div>
            <div class="topic">INTERIOR/EXTERIOR</div>
          </div>
          <div>
            <div class="rows">
              <span class="green"><input type="checkbox" id="green"></span>
              <span class="yellow"><input type="checkbox" id="yellow"></span>
              <span class="red"><input type="checkbox" id="red"></span><p class="info">Head Lights /Tail Lights / Turn Signals / Brake Lights /<br> Hazard Warning Lights /Exterior Lamps / License Plate Lights</p>
            </div>
            <div class="rows">  
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Windshield Washer Spray / Wiper Operation / Wiper Blades</p>
            </div>
            <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
             <span class="red"><input type="checkbox"></span><p class="info">Windshield Condition (Inspect for Cracks, or Pitting)</p>
            </div>
            <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Mirrors / Glass</p>
            </div>
            <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Emergency Brake Adjustment</p>
            </div>
            <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Horn Opeation</p>
            </div>
            <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Fuel Tank Cap Gasket</p>
            </div>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Air Conditioning Filter (if equipped)</p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Clutch Operation (if equipped)</p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Back-up Lights Left / Right</p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Dash Warning Lights</p>
          </div>
          <div class="rows end">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Carpet / Upholstery / Floor Mats</p>
          </div>
          <div>
            <div>
              <div class="topic">UNDER VECHILE</div>
            </div>
            <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Shock Absorp / Suspension / Struts</p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Steering Gear Box / Linkage and Boots / Ball Joints / Dust Covers</p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Muffler / Exhaust Pipes / Mountings / Catalytic Converter</p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Carpet / Upholstery / Floor Mats</p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Engine Oil and / or Fluid Leaks</p>
          </div>
          <div>
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Drive Shaft Boots/ Constant Velocity Boots/ U-joints / <br>Transmision Linkage(it equipped) </p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Transmission / Differential / Transfer Case (Check Fluid Level),<br> Fluid Condition and Fluid Leaks</p>
          </div>
          <div class="rows">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Fuel Lines and Connections / Fuel Tank Band /<br> Fuel Tank Vapor Vent Systems Hoses</p>
          </div>
          <div class="rows end">
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Inspect Nuts and Bolts on Body Chassis</p>
          </div>
        </div>
        <div>
          <div>
              <div class="topic">UNDER HOOD</div>
            </div>
            <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Fluid Levels / Coolant / Battery / Pomer Steering / <br> Brake Fluid/ Washer / Automatic Transmision  </p>
          </div>
          <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Engine Air Filter</p>
          </div>
          <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Drive Belts (Condition and adjustment)</p>
          </div>
          <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Cooling System Hoses / Heater Hoses / Air Conditioning / Hoses and Connections</p>
          </div>
          <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Radiator Core / Air Conditioning Condenser(if equipped)</p>
          </div>
          <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Coolant Recovery Reservior Fluid Level / Condition</p>
          </div>
          <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Cluth Reservior Fluid / Condition (As equipped)</p>
          </div>  
        </div>
        <div>
          <div>
              <div class="topic">COMMENTS / ESTIMATES</div>
            </div>
            <div>
              <textarea name="" id="" cols="30" rows="10"></textarea>
            </div>
        </div>
      </div>
      <div class="tab2">
        <div>
            <div class="green-head">CHECKED AND OKAY</div>
            <div class="yellow-head ">MAY NEED FUTURE ATTENTION</div>
            <div class="red-head">REQUIRES IMMEDIATE ATTENTION</div>
            <div class="topic">INTERIOR/EXTERIOR</div>
          </div>
          <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Battery Terminate / Cables / Mountings</p>
          </div> 
          <div class="rows"> 
              <span class="green"><input type="checkbox"></span>
              <span class="yellow"><input type="checkbox"></span>
              <span class="red"><input type="checkbox"></span><p class="info">Check Condition of Battery (Storge Capacity Test)</p>
          </div> 
          <div class="rows side"> 
              <span class="green"><input type="checkbox"></span><p class="info">Pass</p>
              <span class="yellow"><input type="checkbox"></span><p class="info">Recharge Retest</p>
              <span class="red"><input type="checkbox"></span><p class="info">Fail</p>
              <div>
                <div class="spilt">
                  <p class="info">Factory Spec Cold <br> Cranking Amps</p>
                  <div class="box"></div>
                </div>
                 <div class="spilt">
                  <p class="info">Actual Cold <br> Cranking Amps</p>
                  <div class="box"></div>
                </div>
              </div>
          </div>
          <div class="grey">
            <div>
              <div class="topic">BRAKE AND TIRE</div>
            </div>
            <div class="slip">
              <p class="info">Left Front</p>
              <p class="info">Right Front</p>
            </div>
            <div class="slip">
              <div class="boxed">
                <div>
                  <span class="green"><input type="checkbox"></span>
                  <span class="yellow"><input type="checkbox"></span>
                  <span class="red"><input type="checkbox"></span><p class="info">Break Lining _______mm</p>
                </div>
                <div>
                  <span class="green"><input type="checkbox"></span>
                  <span class="yellow"><input type="checkbox"></span>
                  <span class="red"><input type="checkbox"></span><p class="info">Tire Tread _______32nds</p>
                </div>
                <div>
                  <span class="green"><input type="checkbox"></span>
                  <span class="yellow"><input type="checkbox"></span>
                  <span class="red"><input type="checkbox"></span><p class="info">Wear Pattern _________</p>
                  <p class="info mid">Tire Pressure PSI</p>
                  <div class="dis">
                    <p class="info">Before_______</p> 
                    <p class="info">After _______</p>
                  </div>
                </div>
              </div>
              <div class="boxed">
                    <div>
                      <span class="green"><input type="checkbox"></span>
                      <span class="yellow"><input type="checkbox"></span>
                      <span class="red"><input type="checkbox"></span><p class="info">Break Lining _______mm</p>
                    </div>
                    <div>
                      <span class="green"><input type="checkbox"></span>
                      <span class="yellow"><input type="checkbox"></span>
                      <span class="red"><input type="checkbox"></span><p class="info">Tire Tread _______32nds</p>
                    </div>
                    <div>
                      <span class="green"><input type="checkbox"></span>
                      <span class="yellow"><input type="checkbox"></span>
                      <span class="red"><input type="checkbox"></span><p class="info">Wear Pattern _________</p>
                      <p class="info mid">Tire Pressure PSI</p>
                      <div class="dis">
                        <p class="info">Before_______</p> 
                        <p class="info">After _______</p>
                      </div>
                    </div>
              </div>

            </div>
            <div class="slip">
              <div>
                <span class="green"><input type="checkbox"></span>
                <span class="yellow"><input type="checkbox"></span>
                <span class="red"><input type="checkbox"></span><p class="info">Rotor / Drum</p>
                <div>
                  <span class="yellow"><input type="checkbox"></span><p class="info">Alignment Check needed</p>
                </div>
              </div>
              <div>
                <img class="tire" src="../assets/trye.jpg" alt="trye">
              </div>
              <div>
                <span class="green"><input type="checkbox"></span>
                <span class="yellow"><input type="checkbox"></span>
                <span class="red"><input type="checkbox"></span><p class="info">Rotor / Drum</p>
                <div>
                  <span class="yellow"><input type="checkbox"></span><p class="info">Wheel Balance needed</p>
                </div>
              </div>
            </div>
            <div class="slip">
              <p class="info">Left Rear</p>
              <p class="info">Right Rear</p>
            </div>
            <div class="slip">
              <div class="boxed">
                <div>
                  <span class="green"><input type="checkbox"></span>
                  <span class="yellow"><input type="checkbox"></span>
                  <span class="red"><input type="checkbox"></span><p class="info">Break Lining _______mm</p>
                </div>
                <div>
                  <span class="green"><input type="checkbox"></span>
                  <span class="yellow"><input type="checkbox"></span>
                  <span class="red"><input type="checkbox"></span><p class="info">Tire Tread _______32nds</p>
                </div>
                <div>
                  <span class="green"><input type="checkbox"></span>
                  <span class="yellow"><input type="checkbox"></span>
                  <span class="red"><input type="checkbox"></span><p class="info">Wear Pattern _________</p>
                  <p class="info mid">Tire Pressure PSI</p>
                  <div class="dis">
                    <p class="info">Before_______</p> 
                    <p class="info">After _______</p>
                  </div>
                </div>
              </div>
              <div class="boxed">
                    <div>
                      <span class="green"><input type="checkbox"></span>
                      <span class="yellow"><input type="checkbox"></span>
                      <span class="red"><input type="checkbox"></span><p class="info">Break Lining _______mm</p>
                    </div>
                    <div>
                      <span class="green"><input type="checkbox"></span>
                      <span class="yellow"><input type="checkbox"></span>
                      <span class="red"><input type="checkbox"></span><p class="info">Tire Tread _______32nds</p>
                    </div>
                    <div>
                      <span class="green"><input type="checkbox"></span>
                      <span class="yellow"><input type="checkbox"></span>
                      <span class="red"><input type="checkbox"></span><p class="info">Wear Pattern _________</p>
                      <p class="info mid">Tire Pressure PSI</p>
                      <div class="dis">
                        <p class="info">Before_______</p> 
                        <p class="info">After _______</p>
                      </div>
                    </div>
              </div>
            </div>
            <div class="slip">
                <div>
                   <span class="green"><input type="checkbox"></span>
                   <span class="yellow"><input type="checkbox"></span>
                   <span class="red"><input type="checkbox"></span><p class="info">Rotor / Drum</p>
                </div>
                <div>
                   <span class="green"><input type="checkbox"></span>
                   <span class="yellow"><input type="checkbox"></span>
                   <span class="red"><input type="checkbox"></span><p class="info">Rotor / Drum</p>
                 </div>
              </div>
              <span><input type="checkbox"><p class="info">Brake Inspection Not Performed This Visit </p></span>
          </div> 
          <div>
              <div class="topic">PRIOR BODY DAMAGE</div>
              <img class="car" src="../assets/car.webp" alt="">
              <div class="dis">
                        <p class="info">ADVISOR:</p> 
                        <p class="info">CUSTOMER ACKNOWLEDGEMENT:</p>
              </div>
          </div>

      </div>
      </section>
      </section>
    
      <section class="btn">
          <button @click="download()">DOWNLOAD PDF</button>
      </section>
      
  </div>
</template>

<script>
import html2pdf from 'html2pdf.js'
export default {
  name: 'Index',
  methods:{
      download(){  
          let element = this.$refs.content
          const opt = {
              margin: 0,
              filename: 'VVIR' + '.pdf',
              image: {type: 'jpeg', quality: 0.98},
              html2canvas: {scale : 2},
              jsPDF: { unit: 'in', format: 'letter', orientation: 'portrait'}
          }  
           html2pdf().set(opt).from(element).save()  
  }
  
}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container {
  padding: 1% 3% 2% ; 
  h1{
    text-align: center;
  }
}

.head{
  display: flex;
  justify-content: space-evenly;
}
.table{
  display: flex;
  justify-content: space-between;
}
.tab1{
  width: 49%;
  border: 1px solid #000;
}
.tab2{
  width: 49%;
  border: 1px solid #000;
}

.rows{
  border: 1px solid #000;
}

.info{
  display: inline-block;
  margin: 6px 0 0 4px;
}
.green-head{
  background-color: green;
  color: #fff;
}
.yellow-head{
  background-color: yellow;
  color: #000;
}
.red-head{
  background-color: red;
  color: #fff;
}
.topic{
  background-color: #000;
  color:#fff;
  text-align: center;
}
.end{
  margin-bottom: 5px;
}
.green{
  border: 0.25em solid green;
  width: 1.4em;
}
.yellow{
 border: 0.25em solid yellow;
  width: 1.4em; 
}
.red{
  border: 0.25em solid red;
  width: 1.4em;
}
.box{
  width: 4em;
  height: 1.5em;
  border: 1px solid #000;
  margin-left: 5px;
}
.spilt{
  display: flex;
  align-items: center;
}
.side{
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}
.grey{
  background-color: #DCDEDF;
}
.slip{
 display: flex;
 justify-content: space-between;
}

.boxed{
  background-color: #fff;
  width: 45%;
  border: 1px solid #000;
}

.mid{
  text-align: center;
}
.dis{
  display: flex;
  justify-content: space-between;

}
.car{
  width: 100%;
}

.btn{
    display: flex;
    justify-content: center;
    align-items: center;
}

button{
    margin: 10px 0;
    width: 10rem;
    height: 2rem;
    background-color: blue;
    color: #fff;
    border: none;
    border-radius: 3px;
}
button:hover{
    cursor: pointer;
}

@media only screen and (min-width: 320px) and (max-width: 475px){
    .table{
        display: flex;
        flex-direction: column;
    }
    .tab1{
        width: 100%;
    }
    .tab2{
        width: 100%;
    }
    .side{
        flex-direction: column;
    }
    .tire{
        width: 85%;
    }
}
</style>
