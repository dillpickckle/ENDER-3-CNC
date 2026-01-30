This is an affordable mini CNC mill built from Ender 3 parts. It’s suitable for tasks such as milling, engraving, drawing, and PCB fabrication. The machine is driven by NEMA 17 motors, belts, and two lead screws. It uses an old Dremel that I had lying around as a spindle, and I also made an enclosure out of acrylic and plywood. It use klipper software to run, with a "Klipperized" post-processor to make work on Fusion 360 CAM. Credit to @IMLAB, @SGD_Knuffel, and the team at Ender CNC for providing most of the printables. I used a mix of those files to create an Ender-3 CNC that I felt was most optimized. I made this so I can level up my future projects with acrylic and aluminum parts without having to pay a bunch to get them milled. I also hope to continue working on improving those files in the coming weeks and possibly even mill the sides out of aluminum. Other than using those files, I did not follow any specific guide and did everything else myself. 


Picture of it 

![Pic](https://github.com/dillpickckle/ENDER-3-CNC/blob/main/Images/IMG_2298%20(1).JPG)






Wiring Diagram 



![Wiring](https://github.com/dillpickckle/ENDER-3-CNC/blob/main/Images/Wiring.png)

As you can see, it's pretty simple. Just connect the xyz ports to their respective motors and do the same with the endstops. Also, make sure to connect the board to the ender power supply. 






 
BOM: 
1 x Ender 3 

2 x Linear Rails 150mm MGN12H [Link for Amazon](https://www.amazon.com/uxcell-Sliding-Carriage-Plastic-Printers/dp/B0D54L8LH4/ref=sr_1_6?crid=287LQS7E8O55J&dib=eyJ2IjoiMSJ9.PBFFzAf-3V3mMDOd_jZAG9oEk6bbyrLmu-Qt8KKKuPm5w9VggbNQLru0LygEfNiDs9PDqF_8MeEEK5CtdKRAZy5r8aEIgRv-cKGNJ4v85mAc-PDEBYPEq-MkTnYCu3-5lhPibzRXtiIzOcBHmFjlKkl-_qnNBLiTam0m5lgLkquzWKgonjjqMIqnQx_NHt4VUKuRjYUUzmxtGwvni9g2bcj58qnhVz9A_SEIaO326NM.7aclnAlGecOTjOav1Sf00nQXDaeRtxJ6b0xKrZi9Gt8&dib_tag=se&keywords=mgnh12+linear+rails+150mm&qid=1769805971&sprefix=mgnh12+linear+rails+150mm+%2Caps%2C136&sr=8-6)

1 x  Mscrew assortment kit  [Link for Amazon](https://www.amazon.com/uxcell-Sliding-Carriage-Plastic-Printers/dp/B0D54L8LH4/ref=sr_1_4?dib=eyJ2IjoiMSJ9.boNUj94bBVBEeonkR41UWtri19AnxgVu9sQmBxJT_JXTpSzX7LpHEvj_6jqwKAZ1FNyxosHmyjMNUeSS5Im4ZvRDd1HeMscyVnyXi2Uza1VUSxRxjIQ6YWxqYUgH4WoFxyXZPppthYlu1MUUos90_iulW5zHi0wiYNVMX4xIWxx1sGZ7TRRDMlful_rw3yBhlTque1zzdI86oUyPiiIwLM-wnZ_fc0iVwybJy9YYYEI.cite6YLnLz6Yi3Ss2dzZqjcsNXnyMfirn_TDlB1iUl8&dib_tag=se&keywords=mgn12h+150mm&qid=1769812760&sr=8-4)

1 x Brass heat threaded insert assortment kit [Link for Amazon](https://www.amazon.com/Ktehloy-Threaded-Assortment-Printing-Components/dp/B0CLKDPN65/ref=sr_1_3?crid=82WMPUXV8DRG&dib=eyJ2IjoiMSJ9.DGW1I2sdUlWBQMbecRdN1s2hRrajq4vm0CLsccv2w-CNESGE_RdVpTgXOZ9MHuwhvxy8Acto2oPkpLRygI99clF7qd1G-huDYqano9_nFWywnpFyLAOT8B26LUbymQt2k4sx2tASp4M0wQyuW2kWUFus99oXePV5N03EOhbRMVaMi2Iq9uMM__P-CqjFv2qdgz6zx8zjX9eT4ct5o4TbOt6mFZdbQdpNB06X158UFoOFYoVPqd7FsjsLFkXV2MPgBG2AkqhS_bBOU6mt_iRDAM3yR3Dw7WAhzWekK5nA_2U.G6weU5fyox9RgkEPTwRZd3KSjxRov2ecTUayEXA6UzU&dib_tag=se&keywords=Brass%2Bheat%2Bthreaded%2Binsert%2Bassortment%2Bkit&qid=1769812823&s=hi&sprefix=brass%2Bheat%2Bthreaded%2Binsert%2Bassortment%2Bkit%2B%2Ctools%2C123&sr=1-3&th=1)

32 x M5 T-Nuts [Link for Amazon](https://www.amazon.com/Glarks-European-Assortment-Aluminum-Profile/dp/B07DFG2Y4Q/ref=sr_1_12?crid=1P9PNV5NN5G32&dib=eyJ2IjoiMSJ9.3r-sJVEfStiRkhZs5w4uurv9naGAogvWgZCqNjhsjBWtdTI4p-XQqnNykfrF8Ylb3ilTeWvP2X3YRuiz1Byz45udR78yeFho1w_n8tab-I4r5zI4wFGMpryJwjQKnXLHqqgFAS7odKDXBxy5qAphFp5hW2O-o33-_6m-QyUoWk3ydXE7Ge4ZtVSl1zcQfRoLmsrwzjXcic3n7KK1GiHYEpqp05zmvEjmuefXMpp_2eJ3HfHsAgXkCg0oaEXsfvx0lvq7TOqaqqY_UIAC4YoI5MtVVDf_DdgnbOIMnp3uyak.BRZ31xwisl9snasshrG6PsB1JzzsZ2oVjOC2JDvW264&dib_tag=se&keywords=Tnut%2Blinear%2Brail%2Bassortment%2Bkit&qid=1769812898&s=hi&sprefix=tnut%2Blinear%2Brail%2Bassortment%2Bkit%2Ctools%2C116&sr=1-12&th=1)

1 x Appropriate Spindle (I used an old Dremel, which I had lying around)

2 x ball bearings (I used ones that came on ender 3 tensioner)  

2 x GT2 clip [File](https://www.thingiverse.com/thing:2523813)

All 3d Printed Parts in CAD Folder
