<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diet calculator</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <style>
        .bg-primary-light {
            background-color: #e3f2fd;
        }

        .max-w-\[300px\] {
            max-width: 400px;
        }

        .calculator-header {
            border: 1px dashed #0494fb;
            border-top: 0;
        }
    </style>
</head>

<body>
    <main>
        <div id="diet-calculator" class="container pb-4 px-4 border rounded my-4">

            <form action="" id="diet-calc-form">
                <div class="py-3 mb-4 bg-primary-light">
                    <h3 class="text-center mb-0">Diet Calculator</h3>
                </div>
                <div class="row">
                    <div class="col-12 col-sm-4 mb-3">
                        <label for="weight" class="form-label"><strong>Weight</strong> in kg</label>
                        <input type="number" id="wight" class="form-control" name="weight" aria-label="Weight" />
                    </div>
                    <div class="col-12 col-sm-4 mb-3">
                        <label for="height" class="form-label"><strong>Height</strong> in cm</label>
                        <input type="number" id="height" class="form-control" name="height" aria-label="Height" />
                    </div>
                    <div class="col-12 col-sm-4 mb-3">
                        <label for="age" class="form-label"><strong>Age</strong></label>
                        <input type="number" id="age" id="age" class="form-control" name="age" aria-label="Age" />
                    </div>
                </div>

                <div class="row mb-3">
                    <label class="form-label"><strong>Gender</strong></label>
                    <div class="d-flex">
                        <div class="form-check mx-2">
                            <input class="form-check-input" type="radio" name="gender" id="gender-male" value="male"
                                checked>
                            <label class="form-check-label" for="gender-male">Male</label>
                        </div>
                        <div class="form-check mx-2">
                            <input class="form-check-input" type="radio" name="gender" id="gender-female"
                                value="female">
                            <label class="form-check-label" for="gender-female">Female</label>
                        </div>
                    </div>
                </div>

                <div class="row mb-3">
                    <label class="form-label"><strong>Life style</strong></label>
                    <div class="">
                        <div class="form-check mx-2">
                            <input class="form-check-input" type="radio" name="lifestyle" id="lifestyle-sedentary"
                                value="sedentary" checked>
                            <label class="form-check-label" for="lifestyle-sedentary">Sedentary <span
                                    class="text-muted">( little / no exercise )</span></label>
                        </div>
                        <div class="form-check mx-2">
                            <input class="form-check-input" type="radio" name="lifestyle" id="lifestyle-lightly-active "
                                value="lightly active" checked>
                            <label class="form-check-label" for="lifestyle-lightly-active ">Lightly active <span
                                    class="text-muted">( lite exercise / sports 1-3 days per week )</span></label>
                        </div>
                        <div class="form-check mx-2">
                            <input class="form-check-input" type="radio" name="lifestyle"
                                id="lifestyle-moderately-active" value="moderately active" checked>
                            <label class="form-check-label" for="lifestyle-moderately-active">Moderately active <span
                                    class="text-muted">( moderate exercise / sports 3-5 days per week )</span></label>
                        </div>
                        <div class="form-check mx-2">
                            <input class="form-check-input" type="radio" name="lifestyle" id="lifestyle-very-active"
                                value="very active" checked>
                            <label class="form-check-label" for="lifestyle-very-active">Very active <span
                                    class="text-muted">( hard exercise / sports 6-7 days per week )</span></label>
                        </div>
                        <div class="form-check mx-2">
                            <input class="form-check-input" type="radio" name="lifestyle" id="lifestyle-extra-active"
                                value="extra active" checked>
                            <label class="form-check-label" for="lifestyle-extra-active">Extra active <span
                                    class="text-muted">( very hard exercise / sports and physical job / 2X training
                                    )</span></label>
                        </div>
                    </div>
                </div>

                <div class="row mb-3">
                    <div class="col">
                        <label for="extra-calories" class="form-label"><strong>Add / Cut calories for weight gain /
                                loss</strong></label>
                        <input type="number" id="extra-calories" class="form-control " name="extra_calories"
                            aria-label="Extra calories" placeholder="+/- 1000">
                    </div>
                </div>

                <div class="row mb-3">
                    <label class="form-label"><strong>Diet goal</strong></label>
                    <div>
                        <select class="form-select" name="goal" aria-label="Default select example">
                            <option value="maintain-body-weight" selected>Maintain body weight</option>
                            <option value="weight-gain">Weight gain</option>
                            <option value="weight-loss">Weight loss</option>
                            <option value="diabetes-control">Diabetes control</option>
                        </select>
                    </div>
                </div>

                <div class="d-flex justify-content-center">
                    <button type="submit" class="btn btn-success w-100 max-w-[300px]">Calculate</button>
                </div>
            </form>
        </div>

        <div id="diet-result" class="py-4 bg-primary-light d-none">
            <div class="container">
                <h3 class="text-center">Results</h3>
                <div id="result"></div>
            </div>
        </div>

        <div class="d-none mx-3"></div>
    </main>

    <script>
        // Variables HTML Elements
        const dietCalculator = document.getElementById('diet-calculator');
        const dietForm = document.getElementById('diet-calc-form');
        const dietResult = document.getElementById('diet-result');

        // Variables
        let output = null;

        // Event Listeners
        // document.addEventListener( 'DOMContentLoaded', () => {
        //     dietForm.addEventListener( 'submit', calculateDietValues );
        // } );
        dietForm.addEventListener('submit', calculateDietValues);


        // Functions
        function isValidValues( weight, height, age, gender, lifestyle ) {
            return weight > 0 && height > 0 && age > 0 && '' !== gender && '' !== lifestyle;
        }

        function setOutput( val ) {
            output = val;
        }

        function calculateDietValues(e) {
            e.preventDefault();

            let weight = dietForm.querySelector('input[name="weight"]').value;
            let height = dietForm.querySelector('input[name="height"]').value;
            let age = dietForm.querySelector('input[name="age"]').value;
            let gender = dietForm.querySelector('input[name="gender"]').value;
            let lifestyle = dietForm.querySelector('input[name="lifestyle"]').value;
            let extraCalories = dietForm.querySelector('input[name="extra_calories"]').value;
            let goal = dietForm.querySelector('select[name="goal"]').value;


            if ( ! isValidValues( weight, height, age, gender, lifestyle ) ) {
                alert('Please fill all the fields');
                return;
            }

            let _extraCalories;
            if (!extraCalories || extraCalories === '') {
                _extraCalories = 0;
            } else {
                _extraCalories = Number(extraCalories);
            }

            let BMR;
            if (gender === 'male') {
                BMR = 66 + (13.7 * weight) + (5 * height) - (6.8 * age);
            } else {
                BMR = 655 + (9.6 * weight) + (1.8 * height) - (4.7 * age);
            }

            BMR = Number(BMR);
            BMR = BMR.toFixed(2);

            let calories;
            switch (lifestyle) {
                case 'sedentary':
                    calories = BMR * 1.2;
                    break;
                case 'lightly active':
                    calories = BMR * 1.375;
                    break;
                case 'moderately active':
                    calories = BMR * 1.55;
                    break;
                case 'very active':
                    calories = BMR * 1.725;
                    break;
                case 'extra active':
                    calories = BMR * 1.9;
                    break;
            }
            if (extraCalories !== '') {
                calories += _extraCalories;
            }
            calories = calories.toFixed(2);

            let proteinNeedInGram = Number(weight);
            let proteinCalories = proteinNeedInGram * 4;
            let nonProteinCalories = calories - proteinCalories;
            let carbsCalories = nonProteinCalories * 0.6;
            let carbsNeedInGram = carbsCalories / 4;
            let rowCarbsNeedInGram = carbsNeedInGram * 0.25;
            let cerealCarbsNeedInGram = carbsNeedInGram * 0.75;
            let fatCalories = nonProteinCalories * 0.4;
            let fatNeedInGram = fatCalories / 9;


            const input = {
                'weight': weight,
                'height': height,
                'age': age,
                'gender': gender,
                'lifestyle': lifestyle,
                'extra calories': _extraCalories,
                'goal': goal,
            }

            const result = {
                'BMR': BMR,
                'calories': calories,
                'protein need in gram': proteinNeedInGram,
                'protein calories': proteinCalories,
                'carbs need in gram': carbsNeedInGram,
                'carbs calories': carbsCalories,
                'row carbs need in gram': rowCarbsNeedInGram,
                'cereal carbs need in gram': cerealCarbsNeedInGram,
                'fat calories': fatCalories,
                'fat need in gram': fatNeedInGram,
            }

            for (let key in result) {
                let num = Number(result[key]);
                num = num.toFixed(2);
                result[key] = num;
            }

            setOutput( result );

            // display result
            displayResult( input, output );
        }
        
        async function displayResult( input, output ) {
            dietResult.classList.remove('d-none');
            dietCalculator.classList.add('d-none');

            let HTML = 
            `<div class="border bg-white mb-5">
                <h5 class="py-2 px-2 mb-0 text-center">Input</h5>
                <table class="table table-striped mb-0">
                    <tbody>
                    <tr>
                        <th>Weight</th>
                        <td>${input.weight}</td>
                    </tr>
                    <tr>
                        <th>Height</th>
                        <td>${input.height}</td>
                    </tr>
                    <tr>
                        <th>Age</th>
                        <td>${input.age}</td>
                    </tr>
                    </tbody>
                </table>
            </div>`;

            HTML += 
            `<div class="border bg-white">
                <h5 class="py-2 px-2 mb-0 text-center">Output</h5>
                <table class="table table-striped mb-0">
                    <tbody>
                    <tr>
                        <th>BMR</th>
                        <td>${output.BMR}</td>
                    </tr>
                    <tr>
                        <th>Calories</th>
                        <td>${output.calories}</td>
                    </tr>
                    <tr>
                        <th>Protein need in gram</th>
                        <td>${output['protein need in gram']}</td>
                    </tr>
                    <tr>
                        <th>Protein calories</th>
                        <td>${output['protein calories']}</td>
                    </tr>
                    <tr>
                        <th>Carbs need in gram</th>
                        <td>${output['carbs need in gram']}</td>
                    </tr>
                    <tr>
                        <th>Carbs calories</th>
                        <td>${output['carbs calories']}</td>
                    </tr>
                    <tr>
                        <th>Row carbs need in gram</th>
                        <td>${output['row carbs need in gram']}</td>
                    </tr>
                    <tr>
                        <th>Cereal carbs need in gram</th>
                        <td>${output['cereal carbs need in gram']}</td>
                    </tr>
                    <tr>
                        <th>Fat calories</th>
                        <td>${output['fat calories']}</td>
                    </tr>
                    <tr>
                        <th>Fat need in gram</th>
                        <td>${output['fat need in gram']}</td>
                    </tr>
                    </tbody>
                </table>
            </div>`;

            dietResult.querySelector('#result').innerHTML = HTML;
        }
    </script>
    <script>
        if ('serviceWorker' in navigator) {
        navigator.serviceWorker.register('/service-worker.js')
            .then((registration) => {
            console.log('Service Worker registered with scope:', registration.scope);
            })
            .catch((error) => {
            console.error('Service Worker registration failed:', error);
            });
        }
    </script>
  
</body>

</html>