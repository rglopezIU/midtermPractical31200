
    <div id="recipe2">
        <!-- <script>
            const petsData = [
                    {
                        petName: "Stella",
                        age: 7,
                        weightInKilos: 24,
                        breed: "Dalmation",
                        pic:
                            "images\\stella.png"
                    },
                    {
                        petName: "Cody",
                        age: 8,
                        weightInKilos: 22,
                        breed: "Corgi",
                        pic:
                            "images\\cody.png"
                    },
                    {
                        petName: "Mango",
                        age: 2,
                        weightInKilos: 11,
                        breed: "Persian",
                        pic:
                            "images\\mango.png"
                    },
                    {
                        petName: "Lucy",
                        age: 4,
                        weightInKilos: 35,
                        breed: "Ball Python",
                        pic:
                            "images\\lucy.png"
                    },
                    {
                        petName: "Buhmie",
                        age: 1,
                        weightInKilos: 28,
                        breed: "Bull-dog",
                        pic:
                            "images\\buhmie.png"
                    }
                ];

            let animalsDiv = document.querySelector("#recipe2");
            let animalsList = document.createElement("ul");
            petsData.forEach((animal) => {
                let listItem = document.createElement("li");
                listItem.textContent = `${animal.petName} is a
                        ${animal.breed}, and is ${animal.age} years old  `;
                let animalImage = document.createElement("img");
                animalImage.src = animal.pic;
                animalImage.style.maxWidth = "75px";
                animalImage.style.maxHeight = "75px";
                listItem.append(animalImage);
                animalsList.append(listItem);
            });
            animalsDiv.append(animalsList);
            document.body.append(animalsDiv);

        </script> -->
    </div>

    <div id="recipe3">
        <!-- <script>
            let soughtAnimals = [];
            petsData.forEach((animal) => {
                if (animal.age >= 2)
                    soughtAnimals.push(animal);
            });

            let soughtAnimalsDiv = document.querySelector("#recipe3");
                let soughtAnimalsList = document.createElement("ul");

                soughtAnimals.forEach((animal) => {
                    let listItem = document.createElement("li");
                    listItem.textContent = `${animal.petName} is a ${animal.breed}, and is ${animal.age} years old`;
                    let animalImage = document.createElement("img");
                    animalImage.src = animal.pic;
                    animalImage.style.maxWidth = "75px";
                    animalImage.style.maxHeight = "75px";
                    listItem.append(animalImage);
                    soughtAnimalsList.append(listItem);
                });

                soughtAnimalsDiv.append(soughtAnimalsList);
                document.body.append(soughtAnimalsDiv);
        </script> -->
    </div>