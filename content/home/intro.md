<script>
  // Array of roles you want to cycle through
  var roles = ["Machine Learning Engineer", "Data Scientist", "Wanderlust", "Data Engineer", "Data Analyst"];
  var currentRoleIndex = 0;

  function updateRole() {
    // Get the element where the role will be displayed
    var roleElement = document.getElementById('role');
    // Update the text content of the element with the current role
    roleElement.textContent = roles[currentRoleIndex];
    // Update the index for the next iteration
    currentRoleIndex = (currentRoleIndex + 1) % roles.length;
  }

  // Set an interval to update the role every 2 seconds (2000 milliseconds)
  setInterval(updateRole, 2000);

  // Initial call to set the first role
  updateRole();
</script>

👋 Hi, there! I'm **Nikhil**, a <span id="role"></span>.
{style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}

Check out my [resumé](/about/) and portfolio below 😍
