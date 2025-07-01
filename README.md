# Password-strength-analysis

## Create a Strong Password and Evaluate Its Strength

A strong password is one you can’t guess or crack using a brute force attack.

Let us analyse the follwing passwords using various tools.

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
