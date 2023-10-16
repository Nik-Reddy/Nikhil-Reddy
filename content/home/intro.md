<script>
  var roles = ["Machine Learning Engineer", "Data Scientist", "Wanderlust", "Data Engineer", "Data Analyst"];
  var currentRoleIndex = 0;

  function updateRole() {
    var roleElement = document.getElementById('role');
    roleElement.innerHTML = roles[currentRoleIndex];
    currentRoleIndex = (currentRoleIndex + 1) % roles.length;
  }

  setInterval(updateRole, 2000);  // Update the role every 2 seconds
  window.onload = updateRole;  // Update the role as soon as the page loads
</script>

👋 Hi, there! I'm **Nikhil**, a <span id="role" style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"></span>.

Check out my [resumé](/about/) and portfolio below 😍
