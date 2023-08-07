# Iteration 1

## auth_register_v1

- Assumes that name_first and name_last are not solely comprised of non-alphanumeric characters 
- Assumes that there are no empty user handles
- Every user is given an unique ID

## channels_create_v1

- Channels with duplicate names are allowed so long as the channel IDs are different
- Every Channel is given an unique ID

## channel_messages_v1s

- Assumes that parameter 'start' is a positive integer