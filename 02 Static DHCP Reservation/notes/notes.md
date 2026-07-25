# Static DHCP Reservation

## Objective

Configure a permanent IP address for my desktop using an OpenWrt DHCP reservation.

## What I changed

- Checked the existing DHCP configuration.
- Confirmed the dynamic address pool started at 192.168.1.100.
- Created a static DHCP reservation for my desktop.
- Assigned the desktop the address 192.168.1.10.
- Renewed the DHCP lease on Windows.

## Testing

- Confirmed the desktop received 192.168.1.10.
- Successfully reached the OpenWrt router.
- Confirmed internet connectivity.
- Confirmed DNS resolution was working.

## What I learned

This project helped me understand how DHCP reservations work, why static addresses are useful, and how devices receive their network configuration automatically while still keeping a predictable IP address.