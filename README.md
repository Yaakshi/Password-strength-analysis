# Password-strength-analysis

## Create a Strong Password and Evaluate Its Strength

A strong password is one you can’t guess or crack using a brute force attack.

Let us analyse the following passwords using various tools.

| Password Example      | Length | Upper | Lower | Number | Symbol | 
| --------------------- | ------ | ----- | ----- | ------ | ------ | 
| `pass123`             | 7      | ❌     | ✅     | ✅      | ❌      | 
| `Welcome2024`         | 11     | ✅     | ✅     | ✅      | ❌      | 
| `@HomeSweetHome2023!` | 19     | ✅     | ✅     | ✅      | ✅      | 
| `xT7!pL#9@wQs`        | 12     | ✅     | ✅     | ✅      | ✅      | 
| `9&Lu@z1^Wr!qMveT`    | 16     | ✅     | ✅     | ✅      | ✅      | 


### https://passwordmeter.com/

| Password Example      | Score | Complexity |
| --------------------- | ------ | -------|
| `pass123`             | 35% | Weak | 
| `Welcome2024`         | 87% | Very Strong | 
| `@HomeSweetHome2023!` | 100% | Very Strong | 
| `xT7!pL#9@wQs`        | 100% | Very Strong | 
| `9&Lu@z1^Wr!qMveT`    | 100% | Very Strong |

### https://nordpass.com/secure-password/

| Password Example      | Time to crack | Strength |
| --------------------- | ------ | -------|
| `pass123`             | < 1 second | Weak | 
| `Welcome2024`         | 7 minutes | Moderate | 
| `@HomeSweetHome2023!` | Centuries | Strong | 
| `xT7!pL#9@wQs`        | 3 years | Strong | 
| `9&Lu@z1^Wr!qMveT`    | Centuries | Strong |

### Tips Learned from Evaluation

- Avoid short passwords, even with numbers (e.g., pass123 is too weak).
- Avoid common patterns and words – Welcome2024 looks good but is easy to guess.
- Use at least 12–16 characters with a random mix of:
  - Uppercase and lowercase letters
  - Numbers
  - Special characters
- Longer = stronger – passwords with 16+ characters are much harder to crack.
- Password managers can help generate and store strong, unique passwords.

### Best practices for creating strong passwords

- The password should be at least 12-15 characters long.
- It should use a combination of letters, numbers, and special characters. Spaces are also allowed.
- It should not be a common word, product, character, name, or anything you can easily find in a dictionary.
- It should be a combination that only you know and others could not easily predict.
- Each password should be unique and you shouldn’t reuse them for several accounts.

### Summary: How Password Complexity Affects Security

- Length and randomness are key: the longer and more random a password, the harder it is to crack.
- Complex passwords (including all character types) drastically increase crack time, making brute-force and dictionary attacks impractical.
- Predictable passwords, even if they seem complex (like Welcome2024), are still vulnerable due to pattern recognition and breach data.
- High-entropy passwords like 9&Lu@z1^Wr!qMveT offer the best protection against all common password attacks.

### Common password attacks

**1. Brute force attack**
- It is the method of generating or guessing passwords and then attempting to use them until attackers eventually gain access.
- An example of this type of attack is hackers generating possible passwords from public details about a user like their birthday and generating unique passwords based on that data.
- If the password is weak, then there are tools available online to automate the brute force attacks.

**2. Dictionary attack**
- It is a method of generating passwords from commonly used words or passphrases, most of which can be found in cracking dictionaries that attackers use.

**3. Rainbow table attack**
- It is a more complex method of brute forcing passwords, usually by generating hashes.
- A hash is an encrypted version of your password.
- An attacker would then reverse search the corresponding hash of the target system or network.
- Once they match a hash in your network, they can then reverse-engineer the plaintext password you use for access.

**4. Credential stuffing**
- Credential stuffing is a method of where attackers use compromised passwords to access multiple accounts using the same credentials.
- People who use the same passwords on different accounts or devices are an easy target for credential stuffing attacks.

**5. Keylogging**
- Keylogging attacks use software designed to record keyboard inputs on a compromised device, which attackers can extract information like passwords and other security credentials from.

**6. Password sniffing**
- The attacker eavesdrops on a network’s incoming and outgoing traffic (unencrypted), fishing for packets that contain passwords that they can then crack and use.

**7. Social engineering attacks**
- This attack relies on psychological approaches to manipulate the target into giving up sensitive information.
