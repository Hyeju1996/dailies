<script>
    let animalId = 1;
     
    const handleChange = function(event) {
      console.log(event.target);
      if (event.target.value === 'puppy') {
        animalId = 237;
      } else if (event.target.value === 'bear') {
        animalId = 433;
      } else if (event.target.value === 'monkey') {
        animalId = 783;
      } else if (event.target.value === 'bird') {
        animalId = 1024;
      } else if (event.target.value === 'walrus') {
        animalId = 1084;
      } else {
        animalId = 1;
      }
    }
  </script>
  