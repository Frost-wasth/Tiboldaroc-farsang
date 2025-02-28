<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tibordalóc Farsang</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
    background: linear-gradient(135deg, #FFD700, #FF6347, #1E90FF); /* Farsangos színek */
    text-align: center;
    font-family: Arial, sans-serif;
}

h1 {
    color: white;
    font-size: 3em;
    font-weight: bold;
    margin-top: 20px;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(3, 1fr); /* Három oszlop */
    gap: 15px;
    max-width: 90%;
    margin: 20px auto;
}

.image-container {
    text-align: center;
}

.image-container img {
    width: 100%;
    height: auto;
    max-width: 300px;
    border-radius: 15px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
}

input[type="checkbox"] {
    margin-top: 10px;
    display: block;
    margin-left: auto;
    margin-right: auto;
}

#downloadBtn {
    padding: 10px 20px;
    background-color: #FFD700;
    font-size: 1.2em;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-top: 20px;
}

#downloadBtn:hover {
    background-color: #FFA500;
}
    </style>
</head>
<body>

    <h1>Tibordalóc Farsang</h1>

    <div class="gallery">
        <!-- 64 kép helye -->
        <!-- Minden kép alatt egy checkbox található, amit be lehet jelölni letöltéshez -->
        
        <!-- Kép 1 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep1.jpg" id="img1">
            <label for="img1"><img src="IMG_3124-Edit.jpg" alt="Kép 1"></label>
        </div>
        
        <!-- Kép 2 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep2.jpg" id="img2">
            <label for="img2"><img src="IMG_3128.jpg" alt="Kép 2"></label>
        </div>
        
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3129.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3130-Edit.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3131.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3138.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3141.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3143.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3146.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3148.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3151.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3154.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3160.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3163.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3166.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3169.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3175.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3176.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3181.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3184.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3186.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3188.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3194.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3202.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3203.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3205.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3210.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3211.jpg" alt="Kép 3"></label>
        </div>

        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3214.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3217.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3225.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3228.jpg" alt="Kép 3"></label>
        </div>
        <!-- Kép 3 -->
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3236.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3240.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3255.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3261.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3276.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3291.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3299.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3313.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3315.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3316.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3321.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3325.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3326.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3332.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3333.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3335.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3342.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3353.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3354.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3355.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3356.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3364.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3368.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3372.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3377.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3379.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3382.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3386.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3391.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3394.jpg"></label>
        </div>
        <div class="image-container">
            <input type="checkbox" class="image-select" data-img="img/kep3.jpg" id="img3">
            <label for="img3"><img src="IMG_3397.jpg"></label>
        </div>
        
        <!-- Ismételd meg a fenti kódot összesen 64 képpel -->
    </div>

    <button id="downloadBtn">Kiválasztott képek letöltése</button>

    <script>
        document.getElementById("downloadBtn").addEventListener("click", function() {
    const selectedImages = document.querySelectorAll(".image-select:checked"); // Kiválasztott képek
    if (selectedImages.length === 0) {
        alert("Nincs kiválasztott kép.");
        return;
    }
    
    selectedImages.forEach(img => {
        let imageURL = img.getAttribute("data-img");
        let link = document.createElement("a");
        link.href = imageURL;
        link.download = imageURL.split("/").pop(); // A fájlnevet az eredetiből veszi
        document.body.appendChild(link);
        link.click();
        document.body.removeChild(link);
    });
});

    </script>
</body>
</html>	
