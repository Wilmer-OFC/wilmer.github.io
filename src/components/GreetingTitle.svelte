<script lang="ts">
  const currentTime = new Date();
  const currentHour = currentTime.getHours();

  let greeting = "";

  if (currentHour >= 5 && currentHour < 12) {
    greeting = "Good morning by UNIFINED OFC (Wilsmac)";
  } else if (currentHour >= 12 && currentHour < 18) {
    greeting = "Good afternoon\nUNIFINED OFC";
  } else {
    greeting = "Good night\nUNIFINED OFC";
  }
</script>

<h1 class="text-3xl font-bold">{greeting}</h1>
