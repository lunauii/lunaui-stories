<script>
    import 'boxicons';

    function redirectToLunaui() {
        window.location.href = 'https://lunaui.cc/';
    }
    
    function redirectToGithub() {
        window.location.href = 'https://github.com/lunauii/lunaui-stories/';
    }
</script>

<div class="hero min-h-screen bg-base-200">
    <div class="hero-content text-center">
      <div class="max-w-xl">
        <h1 class="text-5xl font-bold">503</h1>
        <h2 class="text-3xl text-secondary">Service Unavailable</h2>
        <p class="py-6">This page is currently under construction or maintenance! 
            Please come back at a later time.</p>
        <button class="btn btn-primary" onclick={redirectToLunaui}>Go Home</button>
        <button class="btn btn-secondary btn-outline" onclick={redirectToGithub}>
            Github<box-icon name='github' type='logo' color='white'></box-icon>
        </button>
      </div>
    </div>
  </div>