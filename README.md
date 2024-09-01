# Wash.io 👕

Wash.io is a streamlined solution for efficient laundry management in your hostel. With Wash.io, you can easily reserve a time slot for the washing machine on your floor, ensuring you never have to wait in line. The app provides timely notifications, reminding you of your upcoming bookings and keeping you informed about the machine’s real-time availability. Simplify your laundry routine and enjoy a more organized experience with Wash.io.

<img src="https://cdn.discordapp.com/attachments/883222664066502716/1279666940914434101/showcase-img.png?ex=66d54635&is=66d3f4b5&hm=688f7787d7f5562a952464cbb9372d242bd425e53b5d02e11d5242dcb9d7c2e2&" alt="showcase" height="300"/>

## Features ✨

- **Time Slot Booking**:  Effortlessly book a time slot for the washing machine on your floor.
- **Notification Alerts**: Receive notifications to remind you of your upcoming bookings and any changes.
- **Real-Time Availability**: Check the machine’s availability in real-time to find the most convenient time slot.

## Installation 💾

To run the Wash.io app locally, follow these steps:

1. **Install Flutter**
   Ensure that Flutter is installed on your system.

2. **Clone the repository:**

   ```bash
   git clone https://github.com/KingRain/Washio.git
   cd washio
   ```

3. **Configure Supabase Credentials**
Add your superbase credentials in `/lib/main.dart`
```dart
await Supabase.initialize(
      url: 'https://smth.supabase.co',
      anonKey: 'xyz', // Replace with your Supabase anonymous key
    );
```

4. **Run the App**
Use the following command to run the app:
Run `flutter run`

## Contributing 🦆

We welcome contributions! To contribute:

Clone the GitHub repository.
Make your changes.
Submit a pull request.

## Support ☕

If you find Wash.io helpful and want to support the project, consider
[buying us a coffee.](https://buymeacoffee.com/samjoe.png)