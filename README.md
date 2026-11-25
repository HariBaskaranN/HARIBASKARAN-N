
class Haribaskaran:

    name = "Haribaskaran N"
    location = "Tamil Nadu, India 🇮🇳"
    degree = "BE Computer Science @ Mahendra Engineering College"
    cgpa = 7.75  # Up to 8th semester

    # Web Development Skills & Tools
    stack = [
        "HTML5",
        "CSS3",
        "JavaScript",
        "Bootstrap",
        "Python",
        "MySQL",
        "Git",
        "GitHub",
        "VS Code",
        "Responsive Web Design"
    ]

    currently_learning = [
        "Full Stack Python",
        "Flask",
        "Python Backend Development",
        "Database Management"
    ]

    # Completed Projects
    projects = [
        {
            "name": "Hospital Website",
            "type": "Multi-Page Website",
            "technologies": ["HTML5", "CSS3"],
            "description": "Designed and developed a multi-page hospital website."
        },
        {
            "name": "Car Rental Website",
            "type": "Multi-Page Website",
            "technologies": ["HTML5", "CSS3", "Bootstrap"],
            "description": "Designed and developed a multi-page car rental website."
        }
    ]

    fun_fact = "I built a real-time heart-rate monitor with a ₹200 sensor 💓"

    def motto(self):
        return "Build things that matter. Ship things that work."


# Create profile object
profile = Haribaskaran()

print("Name:", profile.name)
print("Location:", profile.location)
print("Degree:", profile.degree)
print("CGPA:", profile.cgpa)
print("Web Development Stack:", profile.stack)
print("Currently Learning:", profile.currently_learning)
print("Projects:", profile.projects)
print("Fun Fact:", profile.fun_fact)
print("Motto:", profile.motto())
