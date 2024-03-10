<html>
<head>

<style>

  .plot-container {
    margin-bottom: 20px;
    text-align: center; /* Center the iframe plots */
}
  
  .model-container {
  margin-bottom: 20px;
}
.audio-line {
  display: flex;
  justify-content: space-between;
  margin-bottom: 10px;
}
audio {
  width: 28%;
}
</style>
</head>
<body>

<h2>LJSpeech Audio Samples</h2>

<div class="model-container">
  <h3>Ground Truths</h3>
  <div class="audio-line">
    <audio controls>
      <source src="VCTK/ground_truth/LJ001-0028.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/ground_truth/LJ002-0149.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/ground_truth/LJ003-0042.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/ground_truth/LJ004-0169.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/ground_truth/LJ005-0101.wav" type="audio/mpeg">
    </audio>
  </div>
</div>

<div class="model-container">
  <h3>HiFiGAN V1</h3>
  <div class="audio-line">
    <audio controls>
      <source src="VCTK/hifiganv1/LJ001-0028_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv1/LJ002-0149_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv1/LJ003-0042_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv1/LJ004-0169_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv1/LJ005-0101_generated.wav" type="audio/mpeg">
    </audio>
    
   
  </div>
  
</div>


<div class="model-container">
  <h3>QGAN V1</h3>
  <div class="audio-line">
    <audio controls>
      <source src="VCTK/hifiQganv1/LJ001-0028_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv1/LJ002-0149_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv1/LJ003-0042_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv1/LJ004-0169_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv1/LJ005-0101_generated.wav" type="audio/mpeg">
    </audio>
    
  
  </div>
 
</div>

<div class="model-container">
  <h3>HiFiGAN V2</h3>
  <div class="audio-line">
    <audio controls>
      <source src="VCTK/hifiganv2/LJ001-0028_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv2/LJ002-0149_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv2/LJ003-0042_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv2/LJ004-0169_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv2/LJ005-0101_generated.wav" type="audio/mpeg">
    </audio>
    
   
  </div>
 
</div>

<div class="model-container">
  <h3>QGAN V2</h3>
  <div class="audio-line">
    <audio controls>
      <source src="VCTK/hifiQganv2/LJ001-0028_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv2/LJ002-0149_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv2/LJ003-0042_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv2/LJ004-0169_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv2/LJ005-0101_generated.wav" type="audio/mpeg">
    </audio>
    

  </div>
 
</div>

<div class="model-container">
  <h3>HiFiGAN V3</h3>
  <div class="audio-line">
    <audio controls>
      <source src="VCTK/hifiganv3/LJ001-0028_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv3/LJ002-0149_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv3/LJ003-0042_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv3/LJ004-0169_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiganv3/LJ005-0101_generated.wav" type="audio/mpeg">
    </audio>
    
    <!-- Add more audio elements as above, one for each sample -->
  </div>
  <!-- Repeat the .audio-line div for each line of samples for this model -->
</div>


<div class="model-container">
  <h3>QGAN V3</h3>
  <div class="audio-line">
    <audio controls>
      <source src="VCTK/hifiQganv3/LJ001-0028_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv3/LJ002-0149_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv3/LJ003-0042_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv3/LJ004-0169_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="VCTK/hifiQganv3/LJ005-0101_generated.wav" type="audio/mpeg">
    </audio>
  </div>
</div>


<h2>OpenSLR Audio Samples</h2>

<div class="model-container">
  <h3>Ground Truth </h3>
  <div class="audio-line">
    <audio controls>
      <source src="Hindi/ground_truth/0215_098.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="Hindi/ground_truth/0360_003.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="Hindi/ground_truth/2087_089.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="Hindi/ground_truth/5152_096.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="Hindi/ground_truth/5671_088.wav" type="audio/mpeg">
    </audio>    
  </div>
</div>


<div class="model-container">
  <h3>Hindi Vocoder V1 </h3>
  <div class="audio-line">
    <audio controls>
      <source src="Hindi/hifiQganv1/0215_098_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="Hindi/hifiQganv1/0360_003_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="Hindi/hifiQganv1/2087_089_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="Hindi/hifiQganv1/5152_096_generated.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="Hindi/hifiQganv1/5671_088_generated.wav" type="audio/mpeg">
    </audio>
    
  </div>
  
</div>


<h2>Loss Landscape Visualisation</h2>




<h2>HifiGAN V1</h2>

<div class="plot-container">
    <h3>Loss Plot</h3>
    <iframe src="plots/hifiganv1/plot1.html" style="width:600px; height:400px;"></iframe>
</div>

<div class="plot-container">
    <h3>Log Scale Loss Plot</h3>
    <iframe src="plots/hifiganv1/plot2.html" style="width:600px; height:400px;"></iframe>
</div>

<h2>QGAN V1</h2>

<div class="plot-container">
    <h3>Loss Plot</h3>
    <iframe src="plots/QganV1/Qplot1.html" style="width:600px; height:400px;"></iframe>
</div>

<div class="plot-container">
    <h3>Log Scale Loss Plot</h3>
    <iframe src="plots/QganV1/Qplot2.html" style="width:600px; height:400px;"></iframe>
</div>



</body>
</html>

