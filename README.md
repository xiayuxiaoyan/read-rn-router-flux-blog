# read-rn-router-flux-blog
learn RNRF source code notes

## motivation
I got some bugs in my rn project of using react-native-router-flux. When scene A -> B -> c -> B ->A with refresh, the application breackdown when back to A. If i do not setState in componentWillMount of scene B, it is working properly. So i want to find the answer of this bug by read it's source code.
