# Railway-Reservation-System-Project
By using HTLM,CSS
# platform-65
<html>
    <head>
        <title>
            railway reservation
        </title>
        <style>
            *{
                box-sizing: border-box;
            }
            h2{
                background-color: white;
                color: red;
                border: 2px solid green;
                padding: 10px 20px;
                text-align: center;
                text-decoration: none;
                display: inline-block;
                margin-left:40%;
                margin-top: 35px;
            }
            h1.vivek{
                direction: rtl;
            }
            p.ll{
                color:white;
                direction:rtl;
            }
            p.oo{color: white;
                direction:rtl;
            }
ul {
  list-style-type: none;
  margin: 0;
  padding:0;
  overflow:hidden;
  background-color:rgb(83, 128, 10);
}

li {
  float:left;
}

li a, .dropbtn {
  display: inline-block;
  color: white;
  text-align: center;
  padding:20px;
  text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
  background-color: red;
}

li.dropdown {
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: rgb(121, 234, 178);
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}
.dropdown-content a {
  color:yellow;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}
.dropdown-content a:hover {background-color:red;}
.dropdown:hover .dropdown-content {
 display: block;}
</style>
    </head>
    <body>
        <ul>
            <li class="pann"><a href="ammaanuu.html"; target="_blank_">LOGIN</a></li>
            <li><a href="daddy.html"; target="_blank_">REGISTER</a></li>
            <li><a href="hoildays package.html"; target="_blank">HOLIDAY PACKAGES</a></li> 
            <li class="dropdown"><a href="javascript:void(0)" class="dropbtn">FOOD ITEMS</a>
            <div class="dropdown-content">
                <a href="non-veg.html" target="_blank">NON-VEG</a>
                <a href="veg.html"target=_blank_>VEG.MEALS</a>
                <a href="fruits.html" target="_blank">FRUITS</a>
            </div>
            <li><a href="#contacts" ;target="_blank">CONTACTS</a></li>
            </li>   
        </ul>
        <h1 style="text-align:center;margin-top:30px;"><mark>INDIAN RAILWAYS</mark></h1>
        <h2>Booking train tickects</h2>
        <br>
        <form style="color:rgb(89, 249, 8)">
            <label>FROM</label><br><br>
            <input list="train" placeholder="FROM"/>
        <datalist id="train"placeholder="FROM">
            <option>Vijayawada</option>
            <option>Rajamundry</option>
            <option>Punjab</option>
            <option>Guntur</option>
            <option>Jalandhar</option>
            <option>Phagwara</option>
            <option>Jalandhar cantt</option>
            <option>New delhi</option>
            <option>Vishakaptnam</option>
            <option>Mumbai</option>
            <option>Hyderabad</option>
            <option>Uttar pradesh</option>
            <option>Rajasthan</option>
            <option>Gujarat</option>
            <option>Mandhya pradesh</option>
            <option>Bihar</option>
            <option>Odisha</option>
            <option>West bengal</option>
            <option>Tamilnadu</option>
            <option>Kerala</option>
            <option>Manipur</option>
            <option>Chhattisgard</option>
            <option>Goa</option>
            <option>Jammu</option>
            <option>Kashmir</option>
            <option>Ladakh</option>
            <option>Himachal pradesh</option>
            <option>Chandigarh</option>
            <option>Harayana</option>
            <option>Sikkam</option>
            <option>Assam</option>
            <option>Tripura</option>
            <option>Nagaland</option>
            <option>Mizoram</option>
            <option>Gangtok</option>
            <option>Itanagar</option>
            <option>Shillong</option>
            <option>Ranchi</option>
            <option>Aizawl</option>
            <option>Agratala</option>
            <option>Myanmar</option>
            <option>Patna</option>
            <option>Daman</option>
            <otion>Secandrabad</otion>
            <option>Samrlakota</option>
            <option>Kakinada</option>
            <option>Kammam</option>
            <option>Thuni</option>
            <option>Vijayanagram</option>
            <option>Palkollu</option>
            <option>Trupathi</option>
            <option>Ramchandra puram</option>
            <option>Kurnool</option>
            <option>Hyderbad</option>
            <option>Chiheru</option>
            <option>Phagwara Junction</option>
            <OPTION>Jamsher Khas</OPTION>
            <option>Bolina Doaba</option>
            <option>Lyallpur Lc Hlt</option>
            <option>Mauli</option>
            <option>Suchi Pind</option>
            <option>Thanbalke</option>
            <option>Mandhali</option>
        </datalist><br><br>
        <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@48,400,0,0" />
        <span class="material-symbols-outlined" style="color:pink;font-size:40px;margin-left:40px">
          swap_vert
          </span>
          <br>
        <label>TO</label><br><br>
            <input list="too" placeholder="TO"/>
        <datalist id="too">
            <option>Vijayawada</option>
            <option>Rajamundry</option>
            <option>Punjab</option>
            <option>Guntur</option>
            <option>Jalandhar</option>
            <option>Phagwara</option>
            <option>Jalandhar cantt</option>
            <option>New delhi</option>
            <option>Vishakaptnam</option>
            <option>Mumbai</option>
            <option>Hyderabad</option>
            <option>Uttar pradesh</option>
            <option>Rajasthan</option>
            <option>Gujarat</option>
            <option>Mandhya pradesh</option>
            <option>Bihar</option>
            <option>Odisha</option>
            <option>West bengal</option>
            <option>Tamilnadu</option>
            <option>Kerala</option>
            <option>Manipur</option>
            <option>Chhattisgard</option>
            <option>Goa</option>
            <option>Jammu</option>
            <option>Kashmir</option>
            <option>Ladakh</option>
            <option>Himachal pradesh</option>
            <option>Chandigarh</option>
            <option>Harayana</option>
            <option>Sikkam</option>
            <option>Assam</option>
            <option>Tripura</option>
            <option>Nagaland</option>
            <option>Mizoram</option>
            <otion>Secandrabad</otion>
            <option>Samrlakota</option>
            <option>Kakinada</option>
            <option>Kammam</option>
            <option>Thuni</option>
            <option>Vijayanagram</option>
            <option>Palkollu</option>
            <option>Trupathi</option>
            <option>Ramchandra puram</option>
            <option>Kurnool</option>
            <option>Hyderbad</option>
            <option>Chiheru</option>
            <option>Phagwara Junction</option>
            <OPTION>Jamsher Khas</OPTION>
            <option>Bolina Doaba</option>
            <option>Lyallpur Lc Hlt</option>
            <option>Mauli</option>
            <option>Suchi Pind</option>
            <option>Thanbalke</option>
            <option>Mandhali</option>
            <option>A N Dev Nagar</option>
            <option>Abhaipur</option>
            <option>Abhayapuri Asam</option>
            <option>Abohar</option>
            <option>Achalda</option>
            <option>Achhnera Junction</option>
            <option>Adas Road</option>
            <option>Adavali</option>
            <option></option>
        </datalist><br><br>
        <label for="date">DATE</label><br><br>
        <input type="date" id="date">
        <hr>
        <label>CLASS</label><br><br>
        <select>
            <option>All classes</option>
            <option>Ac first class</option>
            <option>Ac 2 tier</option>
            <option>Ac 3 tier</option>
            <option>Ac chair car</option>
            <option>Ac 3 economy</option>
            <option>Exec.chair car</option>
            <option>Sleeper</option>
            <option>First class</option>
            <option>Second sitting</option>
            <option>Vistadome non ac </option>
            <option>vistadome chair car</option>
            <option>vistadome ac</option>
        </select><br><br>
        <p>QUATA</p>
        <select>
            <option>General</option>
            <option>Ladies</option>
            <option>Tatkal</option> 
            <option>Lower berth/sr.citizen</option>
            <option>Premium Tatkal</option>
            <option>Person with disablility</option>
        </select>
    <hr>
    <form style="color:bisque"><br>
    <input type="checkbox" id="checkbox">
    <label for="checkbox">FLEXIBLE WITH DATE</label><br>
    <input type="checkbox" id="krishna">
    <label for="krishna">PERSON WITH DISABILITY</label><br>
    <input type="checkbox" id="kalyan">
    <label for="pavan">TRAINS WITH AVALIABLE BERTH</label><br>
    <input type="checkbox" id="manikanta">
    <label for="manikanta">RAILWAY PASS CONCESSION</label><br>
    <input type="checkbox" id="king">
    <label for="king">STUDENT PASS CONCESSION</label><br>
    <input type="reset">
    <input type="submit" >
    </form>
    <br>
    <HR>
    <h3 style="color:aquamarine"><u>NOTE:</u></h3>
    <h3 style="color:red"><u>Abbreviations Used in Railway Reservation</u></h3>
    <p style="color:white">In railway reservation, certain abbreviations are used to indicate the status of your booking. These include:</p>
     <p style="color:aquamarine"><mark>CNF (Confirmed):</mark>This means you have a confirmed reservation and a seat/berth has been allotted exclusively to you.
    </p> 
    <p style="color:aquamarine"><mark>RAC (Reservation against Cancellation): </mark>This means you have a berth, but you will be sharing it with another passenger. When passengers with confirmed reservation cancel their tickets, RAC tickets get the highest priority. If the status of your RAC ticket remains the same even after the chart preparation, you can board the train.</p>  
    <p style="color:aquamarine"><mark>GNWL (General Waitlist):</mark> This means you don’t have a confirmed berth/seat. You will be allotted a confirmed berth/seat based on cancellations. General Waitlist is the most common waitlist type and typically, passengers who board the train from the originating station or a station that is close to the originating station are included in this list. GNWL has the highest chances of confirmation.</p>
    <p style="color:aquamarine"><mark>CKWL/TQWL (Tatkal Waitlist):</mark> This means you have booked your tickets under the Tatkal quota and you don’t have a confirmed berth/seat. During the chart preparation, GNWL is given priority over CKWL. However, CKWL tickets get confirmed directly without going through the RAC phase.</p>
    <p style="color:aquamarine"><mark>RLWL (Remote Location Waitlist):</mark> Typically, passengers boarding from intermediate stations are included in this waitlist type. Chances of confirmation are less for RLWL as compared to GNWL.</p>
    <p style="color:aquamarine"><mark>PQWL (Pooled Quota Waitlist):</mark> This is a kind of Waitlist that is shared by many small railways stations en route. The entire run has only one PQWL which typically operates only from the station where the train originates. PQWL tickets are issued when you are boarding and de-boarding at two intermediate stations. The chances of confirmation are relatively less for PQWL tickets.
    </p>
    <p style="color:aquamarine"><mark>RSWL (Roadside Waitlist): </mark>This is a kind of waitlist typically issued to passengers who board the trains from the station of origin to a roadside station en route. The chances of confirmation are relatively less for RSWL tickets.
    </p>
    <p style="color:aquamarine"><mark>RLGN (Remote Location General Waiting List): </mark>This refers to the waitlisted tickets booked by passengers under the RLWL quota. In other words, once the booking is done, RLWL becomes RLGN.</p>
    <p style="color:aquamarine"><mark>RQWL (Request Waitlist):</mark> Tickets under this waitlist type are usually issued to passengers who travel from an intermediate station and to an intermediate station, and when their booking is not covered by any other waitlist quotas like GNWL, PQWL, etc.</p>
    <p style="color:aquamarine"><mark>REGRET:</mark> The upper limit allowed for reservation has been reached. You will not be allowed to book tickets even on the waitlist.
    </p>
    <h1 class="vivek"><mark>CONTACTS</mark></h1>
    <p class="ll">Customer Care Numbers : 14646 OR 0755-6610661 / 0755-4090600 (Language: Hindi and English)</p>
    <h3 class="vivek" style="direction:rtl"><mark>SERVICE AT STATIONS</mark></h3>
    <p class="11" style="color:aqua;direction:rtl">Every 10 hours services the train(cleaning)</p>
    <p style="color:aqua;direction:rtl">Service contacts:1800-11-322</p>
    
    <link rel="stylesheet" href="cssstyles.css">
</body>
</html>
