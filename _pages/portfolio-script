function showProjectDescription(thumbnail) {
  // Get the project description element.
  const projectDescription = thumbnail.querySelector('.project-description');

  // Show the project description element.
  projectDescription.style.display = 'block';

  // Add a listener to the thumbnail to hide the project description element when the mouse leaves the thumbnail.
  thumbnail.addEventListener('mouseleave', function() {
    projectDescription.style.display = 'none';
  });
}

// Add a listener to each thumbnail to call the showProjectDescription() function when the user hovers their mouse over the thumbnail.
document.querySelectorAll('.portfolio-thumbnail').forEach(thumbnail => {
  thumbnail.addEventListener('mouseover', function() {
    showProjectDescription(thumbnail);
  });
});
