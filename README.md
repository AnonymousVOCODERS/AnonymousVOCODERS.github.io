<!DOCTYPE html>
<html>
<head>
<style>
.model-container {
  margin-bottom: 20px;
}
.audio-line {
  display: flex;
  justify-content: space-between;
  margin-bottom: 10px;
}
audio {
  width: 18%; /* Adjust as necessary to fit your layout */
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
    
    <!-- Add more audio elements as above, one for each sample -->
  </div>
  <!-- Repeat the .audio-line div for each line of samples for this model -->
</div>

<!-- Repeat the .model-container div for each model you want to include -->
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
    
    <!-- Add more audio elements as above, one for each sample -->
  </div>
  <!-- Repeat the .audio-line div for each line of samples for this model -->
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
    
    <!-- Add more audio elements as above, one for each sample -->
  </div>
  <!-- Repeat the .audio-line div for each line of samples for this model -->
</div>

<div class="model-container">
  <h3>HiFiGAN V2</h3>
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
    
    <!-- Add more audio elements as above, one for each sample -->
  </div>
  <!-- Repeat the .audio-line div for each line of samples for this model -->
</div>

</body>
</html>

