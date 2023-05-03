# App

Gym hub style app.

## RFs

- [x] Should be possible to Sign Up
- [x] Should be possible to authenticate
- [x] Should be possible to get logged user profile
- [ ] Should be possible to get the number of check-ins from logged user
- [ ] Should be possible for the user to get check-in history
- [ ] Should be possible to search nerby gyms
- [ ] Should be possible to search gyms by name
- [x] Should be possible for the user to check-in in a gym
- [ ] Should be possible to validade user's check-in
- [ ] Should be possible to register a gym

## RNs

- [x] User should not be able to Sign Up with the same e-mail already registered
- [ ] User should not be able to check-in twice a day
- [ ] User should not be able to check-in if not close to the gym
- [ ] Check-in can only be validated up to 20 min after being created
- [ ] Check-in can only be validated by admins
= [ ] Gym can only be registered by admins


## RNFs

- [x] User's password must be encrypted
- [x] Data must persist on SQL database
- [ ] All lists of data must be 20 items per page
- [ ] User must be identified by JWT