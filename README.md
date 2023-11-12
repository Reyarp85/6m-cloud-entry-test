# Cloud Infrastructure Engineering - (6 Months) Entry Assessment

## Objective

This assessment aims to test your resourcefulness, the ability to understand IT concepts, and produce a viable answer to the problems listed.

---
## Submission

Use the registration form in NTU SCTP

---
## Expected Audience

- Individuals with an IT background to diversify/expand their skills and/or intending to switch to a cloud engineering role.
    - Those with IT or Engineering degree/diploma, or
    - Those with IT or Engineering experience professionally
- Individuals with systems and infrastructure administration background.
- Individuals who have attended basic infrastructure or cloud courses.
- Individuals without an IT background but want to expand their skills and/or intending to switch to a cloud engineering role.

---

## Problems

Please attempt the solve the problems described:

**Question 1 - IP Address**

What is the Bash command to discover the IP Address of `www.skillsunion.com`?

```sh
$ nslookup baeldung.com
```

---

**Question 2 - Copy a Directory**

What is the command to copy a directory from `~/my_project` to `/etc/projects`?

```sh
cp ~/my_project /etc/projects
```
---

**Question 3 - Shell Scripting**

Implement a bash script that does the follow:
1. Convert a string "one,two,three" into an array delimited by comma (,).
1. Loop through the array and print each element.

```sh
#!/bin/bash
# Define a string separated by commas
string="one,two,three"
# Set the IFS to comma
IFS=','
# Use read to bash split string into array
read -ra myvar <<< "$string"
# Output the array and its length
echo "My array: ${myvar[@]}"
echo "Number of elements in the array: ${#myvar[@]}"
```

---

**Question 4 - System Architecture Diagram**

Use [draw.io](draw.io) to draw a system architecture diagram as described below:

- A load balancer to manage request between 4 application servers.
- The load balancer is connected to the internet gateway.
- All application servers are connected to a cluster of database.
- The cluster of database contains an instance for reading and another instance for writing.
- The database must not be connected to the internet gateway.

Share the link to your image of diagram.
https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Question%204.drawio#R7Vpdc9o4FP01PC5jW%2FiDR0JIu1O2ZcJ0s31ihK3Y2sqWRxYB%2But7BfIXTkhKDDUzZSaJdXR1Jd9zj3Rt0kPjePNB4DT6hweE9Swj2PTQbc%2ByTOQ58Ech2z3iDtEeCAUNtFEJzOkPokFDoysakKxmKDlnkqZ10OdJQnxZw7AQfF03e%2BSsPmuKQ9IA5j5mTfSBBjLao55tlPhHQsMon9k0dE%2BMc2MNZBEO%2BLoCoUkPjQXncn8Vb8aEqeDlcdmPu3uht1iYIIl8y4BMfjXs8Sfy5CbWw%2FTT3z%2BsMP3LHOjFyW1%2BxySAAOgmFzLiIU8wm5TojeCrJCDKrQGt0mbKeQqgCeD%2FRMqtZhOvJAcokjHTvWRD5X9qeN%2FWrW%2BVntuN9rxrbCuNGRE0JpKIHEuk2FYcqea3al%2FpatfKfTVDp6OZ8ZXwybF46RTEIiTyiJ3OehXLygSamA%2BEw12ILRgIwrCkT%2FVkwzpnw8KupBUuNLO%2FwrJ9zSyfny23W2w518xWdzXpdYtl9w%2FL52DZ7hbLe79PmK30TD3LYbD%2BmyVchOpi%2BmUEuHEzmo4%2Bjyf3eT9MV5g0MoWvJKMJGRdFj4ptgLOoyI0nIiSFMmaKl4TNeEYl5Qn0LbmUPK4YjBgNVYdUGXSDdcsHfhTZ1dyBAiZV88ebUNV6fbzOUB%2BnKQM3yvuCcRwslpjhxN%2BNfaSMjTnjYrdodGd7NnIAh%2BEBhQnyvoQn5FhuqKWSzVE2dS9CutjS1WZee63L0s3MTaJq2ZYbtp4A6PjRq2%2F9%2Fbou9FhTYynOF%2FSYgZ7kSNXJinSGs4z6OXxHWe7%2BdNnab5QtGratWz10ximsucwQd9C3azkycO26k%2F1a9bgD%2BouFnJ4RdmNLmE%2Fu%2F1XCN0azGfw2zEbK0Hj3mFJlXEO3NA5hGYzCZnHnM5ougDl1yeN0BRLO4HpOBEhoYVreBn76aRK2IbUDpZlNqXnPKM07m9COV02tCe2EA7QmsiXj%2FvdWJeZ0TGIDc9i3h5VPXW6HW%2B2Z5ea8KjfrGuRmDrumt%2BP1a%2Bf1VpyYZu8i9avbMZXaXj2h0PCyunRf1SW6Bl3ag67p0ruILt%2BjsVer0tNV5nVMZe5BegyMy6rMe1VlzRfAHVSZa3RMZWYzsI04duchnSq7hMhFiCVZ4%2B1veTZ3kFnnsEmhM2xS6FpnorD4Xub3vICrVDNlbXPCC7hf3Fp3rUNnZ35AMd%2B6K5ttb8rvO0mHDY2P2SpTYbOM2%2BZLOXBJ00xlyTqiksxTvIvKGnRYz4EWxAQbd9%2BoflD9mBk2xTVwjP6gqS%2Fz8ERqLX750VeJ3z3BQSNumRT8e%2FHtqnV8P3tkfO1HkJn9AEu8xC%2FGu40gO%2FVTx37m1HGeOXWcs0W0%2BTr5QcCtX09IbXSxkEKz%2FHJ9X0%2BV%2F6KAJj8B
---

**Question 5 - System Error Management**

Alan has deployed his web application to Amazon Web Service. Unfortunately, the web application encountered errors as complained by the customers (public users). Whenever there is a complaint, Alan would take a long time to trace the issue and get back to the customers. 

*Q5A: Which of the following described the scenario given?*

A - The principle of security is not applied.

B - The principle of observability is not applied.

C - The principle of availability is not applied.

D - The principle of performance is not applied.

*Q5B: What do you suggest could be done to improve the situation?*

```
Q5A: B - The principle of observability is not applied.
Q5B: Alan should adopt the best practices of Observability https://aws-observability.github.io/observability-best-practices/
```

---

END
