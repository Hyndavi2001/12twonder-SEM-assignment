# 12twonder-SEM-assignment
# Define the startup name and value proposition
startup_name = "Acme Enterprise"
value_proposition = "The most powerful cloud-based solution for enterprise data management."

# Define the target audience and their pain points
target_audience = "Enterprise IT decision makers"
pain_points = ["Data silos", "Data security and compliance", "Inefficient data management processes"]

# Generate ad headlines and descriptions
ad_headlines = [
    f"Transform your enterprise data management with {startup_name}!",
    f"Simplify your data management with {startup_name}'s cloud solution.",
    f"Say goodbye to data silos with {startup_name}.",
    f"Secure your enterprise data with {startup_name}'s powerful solution.",
    f"Streamline your data management with {startup_name} and increase productivity.",
    f"Get rid of inefficient data management processes with {startup_name}.",
]
ad_descriptions = [
    f"{value_proposition} {pain_points[0]}? Our solution can help!",
    f"{value_proposition} We ensure data security and compliance so you can focus on growth.",
    f"{value_proposition} Say goodbye to manual data management processes.",
    f"{value_proposition} Our cloud solution is designed for enterprises like yours.",
    f"{value_proposition} Unlock the full potential of your enterprise data with {startup_name}.",
    f"{value_proposition} Our solution can help you tackle your data management challenges.",
]

# Print the generated ads
for i in range(len(ad_headlines)):
    print(f"Ad {i+1}:")
    print(ad_headlines[i])
    print(ad_descriptions[i])
    print()
