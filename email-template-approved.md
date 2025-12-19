# Email Template: Terminbestätigung (Approved) - Modern Design

```html
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>Terminbestätigung – InkBro</title>
  <meta name="x-apple-disable-message-reformatting">
</head>
<body style="margin:0; padding:0; background: linear-gradient(135deg, #f5f7fa 0%, #e8ecf1 100%);">
  <!-- Preheader -->
  <div style="display:none; font-size:1px; color:#f5f7fa; line-height:1px; max-height:0; max-width:0; opacity:0; overflow:hidden;">
    Termin bestätigt: %service_name% am %appointment_date_time% bei InkBro
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
                                <td style="background: rgba(76, 175, 80, 0.15); border-left: 4px solid #4CAF50; padding:12px 20px; border-radius:6px;">
                                  <span style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#4CAF50; font-weight:600; letter-spacing:0.5px;">
                                    BESTÄTIGT
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
                    Dein Termin ist bestätigt!
                  </h1>
                  <p style="margin:0 0 8px 0; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:18px; line-height:1.6; color:#4a5568;">
                    Hey <strong style="color:#1a1a1a;">%customer_full_name%</strong>,
                  </p>
                  <p style="margin:0; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:16px; line-height:1.7; color:#4a5568;">
                    Wir freuen uns auf deinen Besuch! Dein Termin wurde erfolgreich bestätigt und ist nun reserviert.
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
                            Deine Termindetails
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
                                    Dein Artist
                                  </div>
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:16px; color:#1a1a1a; font-weight:600;">
                                    %employee_full_name%
                                  </div>
                                </td>
                              </tr>
                              <!-- Date & Time -->
                              <tr>
                                <td style="padding-bottom:16px;">
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:12px; color:#666; font-weight:600; text-transform:uppercase; letter-spacing:0.5px; margin-bottom:4px;">
                                    Datum & Uhrzeit
                                  </div>
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:18px; color:#E52337; font-weight:700;">
                                    %appointment_date_time%
                                  </div>
                                </td>
                              </tr>
                              <!-- Location -->
                              <tr>
                                <td>
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:12px; color:#666; font-weight:600; text-transform:uppercase; letter-spacing:0.5px; margin-bottom:4px;">
                                    Studio Location
                                  </div>
                                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:16px; color:#1a1a1a; font-weight:600; line-height:1.5;">
                                    Feldbergstrasse 102<br>
                                    4057 Basel, Schweiz
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

              <!-- Important Info Box -->
              <tr>
                <td style="padding:0 32px 32px 32px;">
                  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="background:#fffbea; border-left:4px solid #f59e0b; border-radius:8px;">
                    <tbody>
                      <tr>
                        <td style="padding:20px 24px;">
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#92400e; font-weight:600; margin-bottom:6px;">
                            Wichtig
                          </div>
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#78350f; line-height:1.6;">
                            Bitte erscheine pünktlich zu deinem Termin. Falls du verhindert bist, gib uns bitte rechtzeitig Bescheid.
                          </div>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                </td>
              </tr>

              <!-- Registration CTA Button -->
              <tr>
                <td style="padding:0 32px 32px 32px;">
                  <table role="presentation" cellpadding="0" cellspacing="0" border="0" width="100%" style="background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%); border-radius:12px; border:1px solid #e8e8e8;">
                    <tbody>
                      <tr>
                        <td style="padding:28px 24px; text-align:center;">
                          <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:15px; color:#4a5568; line-height:1.6; margin-bottom:20px;">
                            Gerne kannst du dich hier bereits bei uns registrieren, so sparen wir uns diesen Aufwand vor dem Termin 😊
                          </div>
                          <table role="presentation" cellpadding="0" cellspacing="0" border="0" align="center">
                            <tbody>
                              <tr>
                                <td style="border-radius:8px; background: linear-gradient(135deg, #E52337 0%, #c41d2d 100%); box-shadow: 0 4px 12px rgba(229, 35, 55, 0.3);">
                                  <a href="https://docs.google.com/forms/d/e/1FAIpQLSfDc4gGSQb3WPm_0Y3qrgmkzfG_BSFE7XdJjHEuZz0TGc3u_A/viewform" target="_blank" style="display:inline-block; padding:16px 40px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:16px; font-weight:700; color:#ffffff; text-decoration:none; letter-spacing:0.3px;">
                                    Jetzt registrieren
                                  </a>
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

              <!-- Contact Section -->
              <tr>
                <td style="padding:0 32px 40px 32px;">
                  <div style="font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size:14px; color:#666; font-weight:600; margin-bottom:16px; text-transform:uppercase; letter-spacing:0.5px;">
                    Fragen? Wir sind für dich da
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
