# Property Management ER Model

# Task requirements
Please create the ER diagram for the following use cases:
1. A landlord can rent out a separate apartment,the whole building or several apartments to another
party.
2. A landlord can sign a rental contract with one or multiple tenants.
3. One tenant can rent multiple apartments from the same landlord.
4. One tenant can rent multiple apartments simultaneously.
5. A landlord can also be a tenant of anotherlandlord.

# Assumptions made
1. Each property will be listed separately be it a building containing apartments or individual apartment.
2. Each property will have "Parent Property Id" will be applicable for apartments and empty for other case.
3. Property type will be Apartment or Building
4. For one property there will be only one contract at given amount of time.
