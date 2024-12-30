import qrcode as qr

# Generate the QR code
img = qr.make("https://youtu.be/BrX1ck9IyJY?si=KM37pOGX1E5C0V9F")

# Save the QR code image
img.save("youtube_video_link.png")
