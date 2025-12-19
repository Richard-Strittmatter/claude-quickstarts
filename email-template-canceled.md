# Email Template: Termin abgesagt (Canceled) - Modern Design

```html
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>Termin abgesagt – InkBro</title>
  <meta name="x-apple-disable-message-reformatting">
</head>
<body style="margin:0; padding:0; background: linear-gradient(135deg, #f5f7fa 0%, #e8ecf1 100%);">
  <!-- Preheader -->
  <div style="display:none; font-size:1px; color:#f5f7fa; line-height:1px; max-height:0; max-width:0; opacity:0; overflow:hidden;">
    Termin abgesagt: %service_name% am %appointment_date_time% bei InkBro
  </div>

  <!-- Main Wrapper -->
  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="background: linear-gradient(135deg, #f5f7fa 0%, #e8ecf1 100%);">
    <tbody>
      <tr>
        <td align="center" style="padding: 40px 20px;">

          <!-- Container -->
          <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="max-width:640px; background-color:#ffffff; border-radius:16px; box-shadow: 0 10px 40px rgba(0,0,0,0.08); overflow:hidden;">
            <tbody>

              <!-- Header with Gradient -->
              <tr>
                <td style="background: linear-gradient(135deg, #000000 0%, #1a1a1a 100%); padding:0; position:relative;">
                  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%">
                    <tbody>
                      <tr>
                        <td style="padding:32px 32px 24px 32px;">
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:28px; color:#ffffff; font-weight:700; letter-spacing:-0.5px;">
                            INK<span style="color:#E52337;">BRO</span>
                          </div>
                        </td>
                      </tr>
                      <!-- Status Badge -->
                      <tr>
                        <td style="padding:0 32px 32px 32px;">
                          <table role="presentation" cellpadding="0" cellspacing="0" border="0">
                            <tbody>
                              <tr>
                                <td style="background: rgba(239, 68, 68, 0.15); border-left: 4px solid #ef4444; padding:12px 20px; border-radius:6px;">
                                  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#ef4444; font-weight:600; letter-spacing:0.5px;">
                                    ABGESAGT
                                  </span>
                                </td>
                              </tr>
                            </tbody>
                          </table>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </td>
              </tr>

              <!-- Hero Section -->
              <tr>
                <td style="padding:40px 32px 32px 32px;">
                  <h1 style="margin:0 0 16px 0; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:32px; line-height:1.3; color:#1a1a1a; font-weight:700; letter-spacing:-0.5px;">
                    Termin abgesagt
                  </h1>
                  <p style="margin:0 0 8px 0; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:18px; line-height:1.6; color:#4a5568;">
                    Hey <strong style="color:#1a1a1a;">%customer_full_name%</strong>,
                  </p>
                  <p style="margin:0; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:16px; line-height:1.7; color:#4a5568;">
                    Dein Termin wurde abgesagt. Kein Problem – wir freuen uns darauf, dich ein anderes Mal bei uns begrüßen zu dürfen.
                  </p>
                </td>
              </tr>

              <!-- Appointment Details Card -->
              <tr>
                <td style="padding:0 32px 32px 32px;">
                  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="background: linear-gradient(135deg, #fafafa 0%, #f5f5f5 100%); border-radius:12px; border: 1px solid #e8e8e8; overflow:hidden;">
                    <tbody>
                      <!-- Card Header -->
                      <tr>
                        <td style="padding:20px 24px; border-bottom:2px solid #E52337;">
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:13px; color:#666; font-weight:600; text-transform:uppercase; letter-spacing:1px;">
                            Abgesagter Termin
                          </div>
                        </td>
                      </tr>
                      <!-- Card Content -->
                      <tr>
                        <td style="padding:28px 24px;">
                          <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%">
                            <tbody>
                              <!-- Service -->
                              <tr>
                                <td style="padding-bottom:16px;">
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:12px; color:#666; font-weight:600; text-transform:uppercase; letter-spacing:0.5px; margin-bottom:4px;">
                                    Leistung
                                  </div>
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:16px; color:#1a1a1a; font-weight:600;">
                                    %service_name%
                                  </div>
                                </td>
                              </tr>
                              <!-- Artist -->
                              <tr>
                                <td style="padding-bottom:16px;">
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:12px; color:#666; font-weight:600; text-transform:uppercase; letter-spacing:0.5px; margin-bottom:4px;">
                                    Artist
                                  </div>
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:16px; color:#1a1a1a; font-weight:600;">
                                    %employee_full_name%
                                  </div>
                                </td>
                              </tr>
                              <!-- Date & Time -->
                              <tr>
                                <td>
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:12px; color:#666; font-weight:600; text-transform:uppercase; letter-spacing:0.5px; margin-bottom:4px;">
                                    Datum & Uhrzeit
                                  </div>
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:18px; color:#888; font-weight:700; text-decoration:line-through;">
                                    %appointment_date_time%
                                  </div>
                                </td>
                              </tr>
                            </tbody>
                          </table>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </td>
              </tr>

              <!-- CTA Button -->
              <tr>
                <td align="center" style="padding:0 32px 24px 32px;">
                  <table role="presentation" cellpadding="0" cellspacing="0" border="0">
                    <tbody>
                      <tr>
                        <td align="center" bgcolor="#E52337" style="border-radius:6px;">
                          <a href="https://inkbro.ch/termin-buchen/" style="display:inline-block; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:15px; color:#ffffff; text-decoration:none; padding:14px 32px; font-weight:600; letter-spacing:0.5px;">
                            Neuen Termin buchen
                          </a>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </td>
              </tr>

              <!-- What's Next Box -->
              <tr>
                <td style="padding:0 32px 32px 32px;">
                  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="background:#f0f9ff; border-left:4px solid #0ea5e9; border-radius:8px;">
                    <tbody>
                      <tr>
                        <td style="padding:20px 24px;">
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#0c4a6e; font-weight:600; margin-bottom:6px;">
                            Was nun?
                          </div>
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#075985; line-height:1.6;">
                            Gerne kannst du jederzeit einen neuen Termin vereinbaren. Kontaktiere uns einfach – wir finden gemeinsam einen passenden Zeitpunkt.
                          </div>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </td>
              </tr>

              <!-- Contact Section -->
              <tr>
                <td style="padding:0 32px 40px 32px;">
                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#666; font-weight:600; margin-bottom:16px; text-transform:uppercase; letter-spacing:0.5px;">
                    Neuen Termin vereinbaren?
                  </div>
                  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%">
                    <tbody>
                      <tr>
                        <!-- Phone -->
                        <td style="padding:12px; background:#f9fafb; border-radius:8px; width:50%;">
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:12px; color:#888; margin-bottom:4px;">
                            Telefon
                          </div>
                          <a href="tel:+41767681780" style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#E52337; text-decoration:none; font-weight:600;">
                            +41 (0)76 681 17 80
                          </a>
                        </td>
                        <td style="width:12px;"></td>
                        <!-- Email -->
                        <td style="padding:12px; background:#f9fafb; border-radius:8px; width:50%;">
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:12px; color:#888; margin-bottom:4px;">
                            E-Mail
                          </div>
                          <a href="mailto:info@inkbro.ch" style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#E52337; text-decoration:none; font-weight:600;">
                            info@inkbro.ch
                          </a>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </td>
              </tr>

              <!-- Footer -->
              <tr>
                <td style="padding:32px; background:#fafafa; border-top:1px solid #e8e8e8;">
                  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%">
                    <tbody>
                      <tr>
                        <td style="text-align:center;">
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:13px; color:#888; line-height:1.6; margin-bottom:8px;">
                            <strong style="color:#1a1a1a;">InkBro Tattoo Studio</strong><br>
                            Feldbergstrasse 102, 4057 Basel, Schweiz
                          </div>
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:12px; color:#aaa; line-height:1.5;">
                            Diese E-Mail wurde automatisch generiert. Bitte antworte direkt, wenn du Fragen hast.
                          </div>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </td>
              </tr>

            </tbody>
          </table>
          <!-- /Container -->

        </td>
      </tr>
    </tbody>
  </table>
</body>
</html>
```
