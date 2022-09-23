# HTML-CSS-one-page-website
Space Station themed HTML/CSS One Page Website
<!DOCTYPE html>
<html>
<head>
<The Voyager Space Station | Resort>
</head>
<body>
  <ul>
    <a href="#home"></a>
    <li>HOME</li><a href="#gallery"></a>
    <li>GALLERY</li><a href="#contact"></a>
    <li>RESERVATIONS</li>
  </ul>
  <p>The Voyager Space Station</p>
  <p>Explore the wonders of space aboard these fascinating wonders of mankind</p>
  <h1>Reservations</h1>
  <h2>Your adventure is just around the moon. Reserve your flight today!</h2>
  <p>Please provide us with your basic contact information.</p>
  <p>Terms and Conditions</p>
  <p><a href="https://theconversation.com/space-tourism-20-years-in-the-making-is-finally-ready-for-launch-159606?utm_medium=email&amp;utm_campaign=Saturday%20Newsletter%20%20May%201%202021%20-%201935718946&amp;utm_content=Saturday%20Newsletter%20%20May%201%202021%20-%201935718946+CID_1b0ff8a2f642c814f88f78e554e224a8&amp;utm_source=campaign_monitor_us&amp;utm_term=Space%20tourism%20%2020%20years%20in%20the%20making%20%20is%20finally%20ready%20for%20launch">From Humble Beginnings...</a></p><a href="#home">www.theVoyagerSpaceStation.space</a> &nbsp;|&nbsp; © 2021
</body>
</html>
/*---------------------------------------------------
    MENU SELECTION
---------------------------------------------------*/
.menu {
  color: #f00;
  font: bold 12px/18px sans-serif;
  text-align: center;
  display: inline;
  margin: 0% auto;
  padding: 0;
  list-style: none;
  text-decoration: none;
}

.menu li {
  color: #000;
  background-color: rgba(255, 255, 255, 1);
  display: inline-block;
  margin: 0% auto;
  position: relative;
  padding: 15px 4%;
  border: 1px solid #9d9fa2;
  box-shadow: 2px 2px 10px 0 rgba(173, 133, 133, 0.4);
  border-radius: 6px;
  /* background-color: #052136; */
  cursor: pointer;
  transition-property: background;
  transition-duration: 0.4s;
  transition-delay: 0s;
  transition-timing-function: ease-in-out;
}

.menu li:hover {
  color: #f00;
  background-color: rgba(100, 65, 0, 0.4);
}

/*===================================================
    GALLERY SECTION ANIMATION
===================================================*/

.photo {
  position: relative;
  line-height: 0;
  margin-bottom: 2em;
  overflow: hidden;
  border-radius: 8px;
  padding: 1px;
  border: 1px solid #021a40;
  background-color: #ff0;
  box-shadow: 2px 2px 10px 0 rgba(0, 0, 0, 0.6);
}

.photo-container {
  text-align: center;
  margin: 15px auto;
  width: 300px;
  height: 169px;
}

.photo-container img {
  max-width: 100%;
  width: 300px;
  height: 169px;
}

.photo-overlay {
  color: #fff;
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  padding-left: 20px;
  padding-right: 20px;
  justify-content: center; /* For centering text inside the .photo-overlay */
  align-items: center;
  background: rgba(0, 0, 0, 0.5);
}

.white-head {
  color: #c9bdaa;
  margin-top: 5%;
}

/*===================================================
    Photo Overlay Transitions
===================================================*/
.photo-overlay {
  opacity: 0;
  transition: opacity 0.5s;
  border-radius: 10px;
  cursor: pointer;
}

.photo-overlay:hover {
  opacity: 1;
}

.photo img {
  transition: transform 3.5s;
  transform-origin: 50% 50%;
}

.photo:hover img {
  transform: scale(1.5);
}
  


--000000000000dafb6b05e90d8873
Content-Type: text/html; charset="UTF-8"
Content-Transfer-Encoding: quoted-printable

<div dir=3D"auto">=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D=3D
