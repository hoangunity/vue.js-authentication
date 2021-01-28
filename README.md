`FIREBASE` Rules for this project:
{
"rules": {
"coaches": {
".read": true,
".write": "auth != null"
},
"requests": {
".read": "auth != null",
".write": true
},
}
}
