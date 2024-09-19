### Requirements
`brew install expect`

### Sample usage

```
function sshlogin() {
  local pw=$(</Users/iestrera/dev/scripts/.hiddenpassword)
  /Users/iestrera/dev/sample "$pw"
}
```
