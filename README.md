mail_text = """From: stephen@example.edu
Subject: Week 8 worksheet
From: marquard@example.edu
Subject: Files and testing
From: zqian@example.edu
Subject: Office hours
"""

file_out = open("mail_log.txt", "w")
file_out.write(mail_text)
file_out.close()

print("mail_log.txt written")
