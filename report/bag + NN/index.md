<dt>
<!DOCTYPE html>
<html>
<head>
<link href='http://fonts.googleapis.com/css?family=Nunito:300|Crimson+Text|Droid+Sans+Mono' rel='stylesheet' type='text/css'>
<style type="text/css">
body {
  margin: 0px;
  width: 100%;
  font-family: 'Crimson Text', serif;
  background: #fcfcfc;
}
table td {
  text-align: center;
  vertical-align: middle;
}
h1 {
  font-family: 'Nunito', sans-serif;
  font-weight: normal;
  font-size: 28px;
  margin: 25px 0px 0px 0px;
  text-transform: lowercase;
}
.container {
  margin: 0px auto 0px auto;
  width: 1160px;
}
</style>
</head>
<body>

<div class="container">


<center>
<h1>CS 143 Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.527
<p>

<table border=0 cellpadding=4 cellspacing=1>
<tr>
<th>Category name</th>
<th>Accuracy</th>
<th colspan=2>Sample training images</th>
<th colspan=2>Sample true positives</th>
<th colspan=2>False positives with true label</th>
<th colspan=2>False negatives with wrong predicted label</th>
</tr>
<tr>
<td>Kitchen</td>
<td>0.360</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0185.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0038.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0113.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0056.jpg" width=99 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0042.jpg" width=101 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0144.jpg" width=115 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0167.jpg" width=57 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0043.jpg" width=57 height=75><br><small>Office</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.470</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0097.jpg" width=57 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0208.jpg" width=103 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0085.jpg" width=81 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0089.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0124.jpg" width=112 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0084.jpg" width=112 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0083.jpg" width=100 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0088.jpg" width=100 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.300</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0214.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0173.jpg" width=132 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0006.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0007.jpg" width=101 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0122.jpg" width=57 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0117.jpg" width=114 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0103.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0043.jpg" width=101 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.380</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0048.jpg" width=101 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0149.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0093.jpg" width=116 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0100.jpg" width=111 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0097.jpg" width=100 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0053.jpg" width=89 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0102.jpg" width=113 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0010.jpg" width=100 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.690</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0165.jpg" width=111 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0099.jpg" width=125 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0023.jpg" width=90 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0181.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0054.jpg" width=100 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0057.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0183.jpg" width=109 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0032.jpg" width=120 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.390</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0197.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0077.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0121.jpg" width=118 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0016.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0168.jpg" width=112 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0017.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0138.jpg" width=100 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0049.jpg" width=100 height=75><br><small>Forest</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.900</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0224.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0097.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0004.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0015.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0157.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0123.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0103.jpg" width=113 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0062.jpg" width=113 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.330</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0030.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0135.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0003.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0002.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0084.jpg" width=93 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0127.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0041.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0024.jpg" width=75 height=75><br><small>Store</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.320</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0234.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0152.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0088.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0022.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0130.jpg" width=109 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0177.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0099.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0037.jpg" width=75 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.480</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0228.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0130.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0126.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0069.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0005.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0134.jpg" width=113 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0082.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0038.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.760</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0059.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0175.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0022.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0044.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0062.jpg" width=63 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0087.jpg" width=50 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0144.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0002.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.470</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0398.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0331.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0027.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0110.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0036.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0021.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0015.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0118.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.570</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0317.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0311.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0051.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0067.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0056.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0004.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0044.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0074.jpg" width=75 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.540</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0321.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0002.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0081.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0004.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0079.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0125.jpg" width=114 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0069.jpg" width=75 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0018.jpg" width=75 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.940</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0004.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0240.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0066.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0131.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0029.jpg" width=63 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0103.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0109.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0056.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<th>Category name</th>
<th>Accuracy</th>
<th colspan=2>Sample training images</th>
<th colspan=2>Sample true positives</th>
<th colspan=2>False positives with true label</th>
<th colspan=2>False negatives with wrong predicted label</th>
</tr>
</table>
</center>


</div>
</body>
</html>
</dt>
