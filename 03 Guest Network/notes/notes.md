# Guest Network

## Objective

Create an isolated guest Wi-Fi network that allows internet access without allowing access to my main home network.

## What I changed

- Created a new bridge (br-guest).
- Created a separate guest interface using the 192.168.50.0/24 subnet.
- Enabled DHCP for the guest network.
- Created a dedicated guest Wi-Fi SSID.
- Configured a separate firewall zone.
- Allowed guest traffic to access the internet only.

## Testing

- Connected my phone to the guest Wi-Fi.
- Confirmed it received an IP address in the 192.168.50.x range.
- Confirmed internet access was working.
- Confirmed my main router could not be accessed.
- Confirmed my desktop could not be accessed from the guest network.

## What I learned

This project taught me how network segmentation works using separate subnets and firewall rules. I also learned how DHCP, wireless networks and firewall zones work together to isolate guest devices from the main network while still providing internet access.