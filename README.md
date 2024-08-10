#!/usr/bin/python
# -*- coding: utf-8 -*-

class SoftwareDeveloper:

    def __init__(self):
        self.name = "Amanda Andrade"
        self.role = "Software Developer"
        self.language_spoken = ["English", "Portuguese"]
        self.education = [
            "Bachelor's degree in Production Engineering",
            "MBA in Information Technology Business Management",
            "Software Development Diploma"
        ]
        self.hobbies = ["playing games", "reading"]

    def say_hello(self):
        print("Hello! Welcome to my profile. I hope you find something here that catches your interest.")
        print(f"My name is {self.name}.")
        print(f"I am a {self.role}.")
        print(f"I speak {', '.join(self.language_spoken)}.")
        print(f"Education: {', '.join(self.education)}.")
        print(f"My hobbies are: {', '.join(self.hobbies)}.")

me = SoftwareDeveloper()
me.say_hello()


