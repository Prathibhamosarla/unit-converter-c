#include <stdio.h>

// Function to handle temperature conversions
void temperatureConversion() {
    int choice;
    float temp;

    printf("\n-- Temperature Conversion --\n");
    printf("1. Celsius to Fahrenheit\n");
    printf("2. Fahrenheit to Celsius\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    if (choice == 1) {
        // Convert Celsius to Fahrenheit
        printf("Enter temperature in Celsius: ");
        scanf("%f", &temp);
        printf("Temperature in Fahrenheit: %.2f°F\n", (temp * 9/5) + 32);
    } else if (choice == 2) {
        // Convert Fahrenheit to Celsius
        printf("Enter temperature in Fahrenheit: ");
        scanf("%f", &temp);
        printf("Temperature in Celsius: %.2f°C\n", (temp - 32) * 5/9);
    } else {
        printf("Invalid choice!\n");
    }
}

// Function to handle length conversions
void lengthConversion() {
    int choice;
    float length;

    printf("\n-- Length Conversion --\n");
    printf("1. Meters to Feet\n");
    printf("2. Feet to Meters\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    if (choice == 1) {
        // Convert Meters to Feet
        printf("Enter length in meters: ");
        scanf("%f", &length);
        printf("Length in feet: %.2f ft\n", length * 3.28084);
    } else if (choice == 2) {
        // Convert Feet to Meters
        printf("Enter length in feet: ");
        scanf("%f", &length);
        printf("Length in meters: %.2f m\n", length / 3.28084);
    } else {
        printf("Invalid choice!\n");
    }
}

// Function to handle weight conversions
void weightConversion() {
    int choice;
    float weight;

    printf("\n-- Weight Conversion --\n");
    printf("1. Kilograms to Pounds\n");
    printf("2. Pounds to Kilograms\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    if (choice == 1) {
        // Convert Kilograms to Pounds
        printf("Enter weight in kg: ");
        scanf("%f", &weight);
        printf("Weight in pounds: %.2f lbs\n", weight * 2.20462);
    } else if (choice == 2) {
        // Convert Pounds to Kilograms
        printf("Enter weight in pounds: ");
        scanf("%f", &weight);
        printf("Weight in kg: %.2f kg\n", weight / 2.20462);
    } else {
        printf("Invalid choice!\n");
    }
}

// Main function - displays menu and calls conversion functions
int main() {
    int option;

    while (1) {
        // Main menu
        printf("\n=== UNIT CONVERTER ===\n");
        printf("1. Temperature\n");
        printf("2. Length\n");
        printf("3. Weight\n");
        printf("4. Exit\n");
        printf("Choose an option: ");
        scanf("%d", &option);

        // Menu options
        switch (option) {
            case 1: temperatureConversion(); break;
            case 2: lengthConversion(); break;
            case 3: weightConversion(); break;
            case 4:
                // Exit the program
                printf("Exiting... Thank you!\n");
                return 0;
            default:
                printf("Invalid option. Try again.\n");
        }
    }
}
