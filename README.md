api_key = "63239eb1043eb43b75070fa9c37f8468"

cat_breeds_info = {
    "Siamese": {
        "diet": "High-quality cat food, both wet and dry. Ensure a balanced diet with protein, fats, and carbohydrates.",
        "care_tips": "Regular grooming, dental care, and annual vet check-ups. Provide mental stimulation with toys and interaction.",
        "special_traits": "Vocal, social, and affectionate. Known for their striking blue almond-shaped eyes and sleek, slender bodies."
    },
    "Persian": {
        "diet": "High-quality cat food, both wet and dry. Ensure a balanced diet with protein, fats, and carbohydrates.",
        "care_tips": "Daily grooming to prevent matting, regular eye cleaning, and annual vet check-ups. Provide a calm environment.",
        "special_traits": "Long, luxurious coat, flat face, and large, expressive eyes. Known for their gentle and calm demeanor."
    },
    "Maine Coon": {
        "diet": "High-quality cat food, both wet and dry. Ensure a balanced diet with protein, fats, and carbohydrates.",
        "care_tips": "Regular grooming, dental care, and annual vet check-ups. Provide plenty of space and interactive toys.",
        "special_traits": "Large size, tufted ears, and bushy tail. Known for their friendly and sociable nature."
    },
    "Bengal": {
        "diet": "High-quality cat food, both wet and dry. Ensure a balanced diet with protein, fats, and carbohydrates.",
        "care_tips": "Regular grooming, dental care, and annual vet check-ups. Provide plenty of exercise and mental stimulation.",
        "special_traits": "Distinctive spotted or marbled coat, athletic build. Known for their high energy and playful nature."
    },
    "Sphynx": {
        "diet": "High-quality cat food, both wet and dry. Ensure a balanced diet with protein, fats, and carbohydrates.",
        "care_tips": "Regular bathing to remove oil buildup, dental care, and annual vet check-ups. Keep warm with clothing or blankets.",
        "special_traits": "Hairless, wrinkled skin, and large ears. Known for their affectionate and social personality."
    }
}

# Example usage
print(f"API Key: {api_key}\n")
for breed, info in cat_breeds_info.items():
    print(f"Breed: {breed}")
    for key, value in info.items():
        print(f"{key.capitalize()}: {value}")
    print()
