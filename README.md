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

<h2>My Research Audio Samples</h2>

<div class="model-container">
  <h3>Ground Truths</h3>
  <div class="audio-line">
    <audio controls>
      <source src="VCTK/ground_truth/LJ001-0028.wav" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="path/to/audio2.mp3" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="path/to/audio3.mp3" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="path/to/audio4.mp3" type="audio/mpeg">
    </audio>
    <audio controls>
      <source src="path/to/audio5.mp3" type="audio/mpeg">
    </audio>
  </div>
</div>

<div class="model-container">
  <h3>Model 1</h3>
  <div class="audio-line">
    <audio controls>
      <source src="path/to/model1_audio1.mp3" type="audio/mpeg">
    </audio>
    <!-- Add more audio elements as above, one for each sample -->
  </div>
  <!-- Repeat the .audio-line div for each line of samples for this model -->
</div>

<!-- Repeat the .model-container div for each model you want to include -->

</body>
</html>

