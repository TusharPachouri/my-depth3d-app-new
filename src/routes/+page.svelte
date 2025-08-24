<script>
  import Depth3D from '$lib/Depth3D';
</script>

<main class="w-full h-screen flex items-center justify-center bg-gray-100">
  <div class="w-96 h-96">
    <!-- The component will adjust to parent size -->
    <Depth3D
      image={{
        image: '/images/your-image.jpg',
        depth: '/images/your-depth-map.png'
      }}
    />
  </div>
</main>
