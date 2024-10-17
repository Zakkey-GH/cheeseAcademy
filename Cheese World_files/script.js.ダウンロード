document.getElementById('transformButton').addEventListener('click', function() {
    var worldImages = [
        'img/world/world1.jpg',
        'img/world/world2.jpg',
        'img/world/world3.jpg'
    ];
    var cheeseImages = [
        'img/cheese/cheese1.jpg',
        'img/cheese/cheese2.jpg',
        'img/cheese/cheese3.jpg'
    ];

    var randomWorldImage = worldImages[Math.floor(Math.random() * worldImages.length)];
    var randomCheeseImage = cheeseImages[Math.floor(Math.random() * cheeseImages.length)];

    var worldElement = document.getElementById('world');
    if (worldElement.classList.contains('cheese')) {
        worldElement.style.backgroundImage = 'url(' + randomWorldImage + ')';
        worldElement.classList.remove('cheese');
    } else {
        worldElement.style.backgroundImage = 'url(' + randomCheeseImage + ')';
        worldElement.classList.add('cheese');
    }
});
