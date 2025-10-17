from datetime import dat

def days_until_new_year():
    today = date.today()
    new_year = date(today.year + 1, 1, 1)
    return (new_year - today).days

if __name__ == "__main__":
    print(f"Days left until New Year: {days_until_new_year()}")

