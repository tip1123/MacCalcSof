<script>
    function calculateMacros() {
        var gender = document.getElementById('gender').value;
        var activityLevel = document.getElementById('activity-level').value;
        var weight = parseFloat(document.getElementById('weight').value);
        var heightInput = document.getElementById('height').value;

        // Convert height from ft'in format to inches
        var heightArray = heightInput.split("'");
        var heightInInches = parseInt(heightArray[0]) * 12 + parseInt(heightArray[1]);

        // Calculate Total Daily Energy Expenditure (TDEE) based on activity level and gender
        var tdee;
        if (gender === 'male') {
            tdee = calculateMaleTDEE(activityLevel, weight, heightInInches);
        } else {
            tdee = calculateFemaleTDEE(activityLevel, weight, heightInInches);
        }

        // Calculate macros based on the assumption of 40% carbs, 30% protein, and 30% fat
        var proteinPerMeal = (tdee * 0.30) / 4;
        var carbsPerMeal = (tdee * 0.40) / 4;
        var fatPerMeal = (tdee * 0.30) / 9;

        // Display the result
        var resultElement = document.getElementById('result');
        resultElement.innerHTML =
            "Protein per meal: " + proteinPerMeal.toFixed(2) + "g<br>" +
            "Carbs per meal: " + carbsPerMeal.toFixed(2) + "g<br>" +
            "Fat per meal: " + fatPerMeal.toFixed(2) + "g";
    }

    function calculateMaleTDEE(activityLevel, weight, height) {
        // Use an estimation formula (Harris-Benedict equation for men)
        var bmr = 88.362 + (13.397 * weight) + (4.799 * height) - (5.677 * age);
        var activityMultiplier;
        
        switch (activityLevel) {
            case '1-2':
                activityMultiplier = 1.2;
                break;
            case '3-4':
                activityMultiplier = 1.375;
                break;
            case '5-7':
                activityMultiplier = 1.55;
                break;
            default:
                activityMultiplier = 1.2;
        }

        return bmr * activityMultiplier;
    }

    function calculateFemaleTDEE(activityLevel, weight, height) {
        // Use an estimation formula (Harris-Benedict equation for women)
        var bmr = 447.593 + (9.247 * weight) + (3.098 * height) - (4.330 * age);
        var activityMultiplier;
        
        switch (activityLevel) {
            case '1-2':
                activityMultiplier = 1.2;
                break;
            case '3-4':
                activityMultiplier = 1.375;
                break;
            case '5-7':
                activityMultiplier = 1.55;
                break;
            default:
                activityMultiplier = 1.2;
        }

        return bmr * activityMultiplier;
    }
</script>
