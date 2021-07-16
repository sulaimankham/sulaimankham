### Hi there 👋

<!--
**sulaimankham/sulaimankham** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->








<!DOCTYPE html>
<html lang="en">






<!--Template Styling-->

<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">

<style>
body,h1,h2,h3,h4,h5 {font-family: "Poppins", sans-serif}
body {font-size:16px;}
.w3-half img{margin-bottom:-6px;margin-top:16px;opacity:0.8;cursor:pointer}
.w3-half img:hover{opacity:1}
</style>
<body>


<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-red w3-collapse w3-top w3-large w3-padding" style="z-index:3;width:300px;font-weight:bold;" id="mySidebar"><br>
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-hide-large w3-display-topleft" style="width:100%;font-size:22px">Close</a>
  <div class="w3-container">
    <h3 class="w3-padding-64"><b>Automated<br>Inspection<br>Group<br></h3>
  </div>

  <!--Side Menu Names-->
  <div class="w3-bar-block">
    <a href="#" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Home</a> 
    <a href="#services" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Services</a> 
    <a href="#designers" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Report</a> 
    <a href="#packages" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Vision Map</a> 
    <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button w3-hover-white">Contact</a>
  </div>
</nav>

<!-- Top menu on small screens -->
<header class="w3-container w3-top w3-hide-large w3-red w3-xlarge w3-padding">
  <a href="javascript:void(0)" class="w3-button w3-red w3-margin-right" onclick="w3_open()">☰</a>
  <span>AIG</span>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:340px;margin-right:40px">

  <!-- Header -->
  <div class="w3-container" style="margin-top:80px" id="Report">
    <h1 class="w3-jumbo"><b>Vision System</b></h1>
    <h1 class="w3-xxxlarge w3-text-red"><b>Data mining</b></h1>
    <hr style="width:1200px;border:1px solid rgba(156, 94, 94, 0.603)" class="w3-round">
  </div>
  
  <!-- Photo grid (modal) -->
  <div class="w3-row-padding">
    <div class="w3-half">
      <img src="https://www.cognex.com/library/media/blogs/deep-learning-blogs/2020/automotive-industry_large.jpg?sc_lang=en&h=300&w=945&la=en&hash=C6CE698C899385AA128B29EA11A140CB" style="width:100%" onclick="onClick(this)" alt="Image of Deep Learning Inspection">
      <img src="https://images.techhive.com/images/article/2016/11/innovation-imperative-100694176-large.jpg" style="width:100%" onclick="onClick(this)" alt="Breaking barriers with innovation">
    </div>

    <div class="w3-half">
      <img src="https://media-exp3.licdn.com/dms/image/C4E12AQHuOQFtNIHt8g/article-cover_image-shrink_600_2000/0/1567487357243?e=1628121600&v=beta&t=llIeIMV_Ob0XmKFe_iqqvBooNNK87zkRAjqmZMZqMEc" style="width:100%" onclick="onClick(this)" alt="Image of AI smart inspection">
      <img src="https://quantdare.com/wp-content/uploads/2019/06/deep_learning.png" style="width:100%" onclick="onClick(this)" alt="Deep learning is an artificial intelligence(AI) element; that imitates human brain function known as artifical neural network activity">
    </div>
  </div>


  <!-- Modal for full size images on click-->
  <div id="modal01" class="w3-modal w3-black" style="padding-top:0" onclick="this.style.display='none'">
    <span class="w3-button w3-black w3-xxlarge w3-display-topright">×</span>
    <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
      <img id="img01" class="w3-image">
      <p id="caption"></p>
    </div>
  </div>


  <!-- Services Content -->
  <div class="w3-container" id="services" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>Services.</b></h1>
    <hr style="width:1200px;border:1px solid rgba(156, 94, 94, 0.603)" class="w3-round">
    <p>Training</p>
            <ul class = "Table of Training materials">
              <li><a href="https://myteams.toyota.com/:p:/r/sites/QCS-Vision/_layouts/15/Doc.aspx?sourcedoc=%7B9F68785A-3155-4337-9C1B-7BC092DCB7D1%7D&file=Training%20Material%20for%20Automated%20Inspection%20-%20Rev%20C.pptx&action=edit&mobileredirect=true" target="_blank">TRAINING OVERIEW</a></li>
              <li><a href="https://myteams.toyota.com/:b:/r/sites/QCS-Vision/Shared%20Documents/AIG%20Page%20Content/TRAIN/AMA/TMMC%20ICS+%20AMA%20FOR%20QCI.pdf?csf=1&web=1&e=qXZzZf" target="_blank">AMA</a></li>
              <li><a href="https://myteams.toyota.com/sites/QCS-Vision/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=AG8PRB&cid=6315ab6e%2Dbc24%2D442b%2Db1e9%2D35b06e298690&FolderCTID=0x012000F35A6791DEA63B42B50BE0CD0140F72F&viewid=c2afcac1%2Da9e6%2D4623%2D9466%2Df52d86b59890&id=%2Fsites%2FQCS%2DVision%2FShared%20Documents%2FAIG%20Page%20Content%2FTRAIN%2FArcX%2FARCX" target="_blank">ArcX</a></li>
              <li><a href="https://myteams.toyota.com/sites/QCS-Vision/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=AG8PRB&cid=6315ab6e%2Dbc24%2D442b%2Db1e9%2D35b06e298690&FolderCTID=0x012000F35A6791DEA63B42B50BE0CD0140F72F&viewid=c2afcac1%2Da9e6%2D4623%2D9466%2Df52d86b59890&id=%2Fsites%2FQCS%2DVision%2FShared%20Documents%2FAIG%20Page%20Content%2FTRAIN%2FKEYENCE%5FVISION%5FACADEMY%2FBasics" target="_blank">Machine Vision Basic</a></li>
              <li><a href="https://myteams.toyota.com/sites/QCS-Vision/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=AG8PRB&cid=6315ab6e%2Dbc24%2D442b%2Db1e9%2D35b06e298690&FolderCTID=0x012000F35A6791DEA63B42B50BE0CD0140F72F&viewid=c2afcac1%2Da9e6%2D4623%2D9466%2Df52d86b59890&id=%2Fsites%2FQCS%2DVision%2FShared%20Documents%2FAIG%20Page%20Content%2FTRAIN%2FKEYENCE%5FVISION%5FACADEMY%2FIntermediate" target="_blank">MACHINE VISION INTERMEDIATE</a> </li>
              <li><a href="https://myteams.toyota.com/sites/QCS-Vision/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=AG8PRB&cid=6315ab6e%2Dbc24%2D442b%2Db1e9%2D35b06e298690&FolderCTID=0x012000F35A6791DEA63B42B50BE0CD0140F72F&viewid=c2afcac1%2Da9e6%2D4623%2D9466%2Df52d86b59890&id=%2Fsites%2FQCS%2DVision%2FShared%20Documents%2FAIG%20Page%20Content%2FTRAIN%2FKEYENCE%5FVISION%5FACADEMY%2FAdvanced" target="_blank">MACHINE VISION ADVANCED</a> </li>  
              <li><a href="https://myteams.toyota.com/sites/QCS-Vision/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=AG8PRB&cid=6315ab6e%2Dbc24%2D442b%2Db1e9%2D35b06e298690&FolderCTID=0x012000F35A6791DEA63B42B50BE0CD0140F72F&viewid=c2afcac1%2Da9e6%2D4623%2D9466%2Df52d86b59890&sortField=LinkFilename&isAscending=false&id=%2Fsites%2FQCS%2DVision%2FShared%20Documents%2FAIG%20Page%20Content%2FTRAIN%2FVision" target="_blank" >VISION</a> </li>
              <li><a href="https://myteams.toyota.com/sites/QCS-Vision/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=AG8PRB&cid=6315ab6e%2Dbc24%2D442b%2Db1e9%2D35b06e298690&FolderCTID=0x012000F35A6791DEA63B42B50BE0CD0140F72F&sortField=LinkFilename&isAscending=false&viewid=c2afcac1%2Da9e6%2D4623%2D9466%2Df52d86b59890&id=%2Fsites%2FQCS%2DVision%2FShared%20Documents%2FAIG%20Page%20Content%2FTRAIN%2FImage%20Processing" target="_blank">IMAGE PROCESSING</a></li>
              <li><a href="https://myteams.toyota.com/sites/QCS-Vision/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=AG8PRB&cid=6315ab6e%2Dbc24%2D442b%2Db1e9%2D35b06e298690&FolderCTID=0x012000F35A6791DEA63B42B50BE0CD0140F72F&sortField=LinkFilename&isAscending=false&viewid=c2afcac1%2Da9e6%2D4623%2D9466%2Df52d86b59890&id=%2Fsites%2FQCS%2DVision%2FShared%20Documents%2FAIG%20Page%20Content%2FTRAIN%2FProcess%20flow" target="_blank">PROCESS FLOW</a> </li>
              <li><a href="https://myteams.toyota.com/:p:/r/sites/QCS-Vision/_layouts/15/Doc.aspx?sourcedoc=%7B9F68785A-3155-4337-9C1B-7BC092DCB7D1%7D&file=Training%20Material%20for%20Automated%20Inspection%20-%20Rev%20C.pptx&action=edit&mobileredirect=true" target="_blank">TRAINING OVERIEW</a></li>
              <li><a href="https://myteams.toyota.com/sites/QCS-Vision/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=AG8PRB&cid=6315ab6e%2Dbc24%2D442b%2Db1e9%2D35b06e298690&FolderCTID=0x012000F35A6791DEA63B42B50BE0CD0140F72F&sortField=LinkFilename&isAscending=false&viewid=c2afcac1%2Da9e6%2D4623%2D9466%2Df52d86b59890&id=%2Fsites%2FQCS%2DVision%2FShared%20Documents%2FTire%20Automated%20Inspection" target="_blank">TIRE SHARE</a></li>
              </ul>  
              </p>
  </div>
  
  <!-- Reporting content-->
  <div class="w3-container" id="designers" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b></b>Reporting</h1>
    <hr style="width:1200px;border:1px solid rgba(156, 94, 94, 0.603)" class="w3-round">
    <p></p>
    <p><b>Daily Updated</b></p>
  </div>

  <!-- Reporting Content in the box -->
  <div class="w3-row-padding w3-grayscale">
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        <img src="https://www.sas.com/el_gr/insights/analytics/data-mining/_jcr_content/par/styledcontainer_55de/image.img.jpg/1614922696226.jpg">
        <div class="w3-container">
          <h3>Vision</h3>
          <p class="w3-opacity"></p>
          <a href="http://v21qcipw01/ICSPLUS/GEN_Daily_Reports/Report%20Web%20Pages/TMMCVISIONREPORT.html" target="_blank"><h3>Vision Daily Report</h3></a>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        
        <div class="w3-container">
          <h3>Down Time</h3>
          <p class="w3-opacity"></p>
          <a href="https://myteams.toyota.com/:b:/r/sites/QCS-Vision/Shar
                  ed%20Documents/00%20-%20Notifications/01%20-%20South%20Plant/QC%20Systems%20Brea
                  kdown%20Sheet%20-%20210122%20Vision%20-%20signed.pdf?csf=1&web=1&e=LfLUBV" target="_blank">Link</a>
        </div>
      </div>
    </div>
    <div class="w3-col m4 w3-margin-bottom">
      <div class="w3-light-grey">
        
        <!--Blank section-->
        <div class="w3-container">
          <h3>Blank</h3>
          <p class="w3-opacity">Blank</p>
          <p>Blank</p>
        </div>
      </div>
    </div>
  </div>


  <!-- Vision Map content -->
  <div class="w3-container" id="packages" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>MAP</b></h1>
    <hr style="width:1200px;border:1px solid rgba(156, 94, 94, 0.603)" class="w3-round">
    <p>Vision System Names and location</p>
  </div>

    <!--Vision System naming-->
  <div class="w3-row-padding">
    <div class="w3-half w3-margin-bottom">
      <ul class="w3-ul w3-light-grey w3-center">
        <li class="w3-dark-grey w3-xlarge w3-padding-32">South</li>
        <li class="w3-padding-16">Instrumental Panel [IP]</li>
        <li class="w3-padding-16">Chassis 2 [CH2]</li>
        <li class="w3-padding-16">Chassis 3 Pit22 [CH3-22]</li>
        <li class="w3-padding-16">Chassis 3 Pit24 [CH3-P24]</li>
        <li class="w3-padding-16">
        </li>
      </ul>
    </div>

    
    <!--Vision System naming-->    
    <div class="w3-half">
      <ul class="w3-ul w3-light-grey w3-center">
        <li class="w3-red w3-xlarge w3-padding-32">West</li>
        <li class="w3-padding-16">Door Line</li>
        <li class="w3-padding-16">Final 3</li>
        <li class="w3-padding-16">Instrumental Panel [IP]</li>
        <li class="w3-padding-16">
        </li>
      </ul>
    </div>


    <!--Vision System naming-->
    <div class="w3-half">
      <ul class="w3-ul w3-light-grey w3-center">
        <li class="w3-red w3-xlarge w3-padding-32">North</li>
        <li class="w3-padding-16">Door Line</li>
        <li class="w3-padding-16">Final 1</li>
        <li class="w3-padding-16">Instrumental Panel [IP]</li>
        <li class="w3-padding-16">
        </li>
      </ul>
    </div>
  </div>
  

  <!-- Contact Content-->
  <div class="w3-container" id="contact" style="margin-top:75px">
    <h1 class="w3-xxxlarge w3-text-red"><b>Contact.</b></h1>
    <hr style="width:1200px;border:1px solid rgba(156, 94, 94, 0.603)" class="w3-round">
    <p>Fill out the form. We love meeting new people!</p>
    <form action="mailto:AutomatedInspectionGroup@internal.tmmc.ca" method="POST" enctype="text/plain target="">
      <div class="w3-section">
        <label>Name</label>
        <input class="w3-input w3-border" type="text" name="Name" required>
      </div>

      <div class="w3-section">
        <label>Email</label>
        <input class="w3-input w3-border" type="text" name="Email" required>
      </div>

      <div class="w3-section">
        <label>Plant</label>
        <select id="PLANT" name="TMMC PLANT">
          <option value="North">North</option>
          <option value="South">South</option>
          <option value="West">West</option>
          <option value="Guest">Guest</option>
        </select>
      </div>

      <div class="w3-section">
        <label>Message</label>
        <input class="w3-input w3-border" type="text" name="Message" required>
      </div>
      <button type="submit"  class="w3-button w3-block w3-padding-large w3-red w3-margin-bottom">Send Message</button>
    </form>  
  </div>

<!-- End page content -->
</div>

<!-- W3.CSS Container -->
<div class="w3-light-grey w3-container w3-padding-32" style="margin-top:75px;padding-right:58px"><p class="w3-right"><a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-opacity"></a></p></div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}
</script>

</body>








<!--Footer and Positioning-->
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Untitled</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ionicons/2.0.1/css/ionicons.min.css">
  <link rel="stylesheet" href="assets/css/style.css">
</head>


<!--HTML FOOTER-->
<body>
  <div class="footer-dark">
      <footer>
          <div class="container">
              <div class="row">
                  <div class="col-sm-6 col-md-3 item">
                      <h3></h3>
                      <ul>
                        <li><a href="#">Contact</a></li>
                        <li><a href="#">Help</a></li>
                        <li><a href="#">Train</a></li>
                      </ul>
                  </div>
                  <div class="col-sm-6 col-md-3 item">
                    <h3>Terms and Conditions</h3>
                    <ul>
                        <li><a href="https://tmmc.ca/en/legal-terms-and-conditions/" target="_blank">Legal Terms and Conditions</a></li>
                        <li><a href="https://tmmc.ca/en/privacy-policy/"target="_blank">Privacy Policy</a></li>
                        <li><a href="https://tmmc.ca/en/accessibility/" target="_blank">Accessibility</a></li>
                    </ul>
                  </div>
                  <div class="col-md-6 item text">
                      <h3>Automated Inspection Group</h3>
                      <p>AIG aims to lead Innovative Visionary solutions. Digging through data to discover patterns and correlations within Big data sets to predict outcomes</p>
                  </div>
                  <div class="col item social">
                      <p>Website Designed By AIG</p>
                  </div>
              </div>
              <p style="text-align: center;">© TMMC 2021 All Right Reserved.</p>
          </div>
      </footer>
  </div>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/js/bootstrap.bundle.min.js"></script>
</body>

<!--FOOTER CSS-->

<style>
  .footer-dark {
      padding:50px 0;
      color:#ffffff;
      background-color:#0c0e0f;
    }
    
    .footer-dark h3 {
      margin-top:0;
      margin-bottom:12px;
      font-weight:bold;
      font-size:16px;
    }
    
    .footer-dark ul {
      padding:0;
      list-style:disc;
      line-height:1.6;
      font-size:14px;
      margin-bottom:0;
    }
    
    .footer-dark ul a {
      color:inherit;
      text-decoration:wavy;
      opacity:0.6;
    }
    
    .footer-dark ul a:hover {
      opacity:0.8;
    }
    
    @media (max-width:767px) {
      .footer-dark .item:not(.social) {
        text-align:center;
        padding-bottom:20px;
      }
    }
    
    .footer-dark .item.text {
      margin-bottom:36px;
    }
    
    @media (max-width:767px) {
      .footer-dark .item.text {
        margin-bottom:0;
      }
    }
    
    .footer-dark .item.text p {
      opacity:0.6;
      margin-bottom:0;
    }
    
    .footer-dark .item.social {
      text-align:center;
    }
    
    @media (max-width:991px) {
      .footer-dark .item.social {
        text-align:center;
        margin-top:20px;
      }
    }
    
    .footer-dark .item.social > a {
      font-size:20px;
      width:36px;
      height:36px;
      line-height:36px;
      display:inline-block;
      text-align:center;
      border-radius:50%;
      box-shadow:0 0 0 1px rgba(255,255,255,0.4);
      margin:0 8px;
      color:#fff;
      opacity:0.75;
    }
    
    .footer-dark .item.social > a:hover {
      opacity:0.9;
    }
    
    .footer-dark .copyright {
      text-align:center;
      padding-top:24px;
      opacity:0.3;
      font-size:13px;
      margin-bottom:0;
    }
  </style>
   













   </html>
