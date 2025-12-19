# Custom CSS für Elementor Kontaktformular

## Primärfarbe: #E52337

```css
/* Kontaktformular Container */
.elementor-widget-form .elementor-form {
    max-width: 700px;
    margin: 0 auto;
    background-color: rgba(30, 30, 30, 0.8);
    padding: 50px 40px;
    border-radius: 8px;
}

/* Labels verstecken (nur Placeholder verwenden) */
.elementor-field-label {
    display: none;
}

/* Wrapper für zweispaltige Felder */
.elementor-form-fields-wrapper {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

/* Input Felder & Textarea */
.elementor-field-textual,
.elementor-field.elementor-field-textual,
.elementor-field input,
.elementor-field textarea {
    background-color: #2a2a2a !important;
    border: 2px solid rgba(255, 255, 255, 0.2) !important;
    color: #ffffff !important;
    padding: 18px 22px;
    border-radius: 6px;
    font-size: 15px;
    transition: all 0.3s ease;
    width: 100%;
}

.elementor-field-textual:focus,
.elementor-field.elementor-field-textual:focus,
.elementor-field input:focus,
.elementor-field textarea:focus {
    background-color: #2f2f2f !important;
    border-color: #E52337 !important;
    outline: none;
}

.elementor-field-textual::placeholder,
.elementor-field input::placeholder,
.elementor-field textarea::placeholder {
    color: rgba(255, 255, 255, 0.5) !important;
    opacity: 1;
}

/* Zweispaltige Felder (Name, Email, Phone, Booking Date, etc.) */
.elementor-field-group-name,
.elementor-field-group-email {
    flex: 1 1 calc(50% - 10px);
    min-width: 250px;
}

/* Einzeilige breite Felder (Message, Subject, etc.) */
.elementor-field-group-message,
.elementor-field-type-textarea,
.elementor-field-type-submit {
    flex: 1 1 100%;
}

/* Textarea spezifisch */
textarea.elementor-field-textual {
    min-height: 180px;
    resize: vertical;
    font-family: inherit;
}

/* Submit Button */
.elementor-button {
    background-color: #E52337;
    color: #ffffff;
    border: none;
    padding: 18px 50px;
    font-size: 15px;
    font-weight: 600;
    letter-spacing: 2px;
    text-transform: uppercase;
    border-radius: 6px;
    cursor: pointer;
    transition: all 0.3s ease;
    width: auto;
    margin-top: 10px;
    display: inline-block;
}

.elementor-button:hover {
    background-color: #c61e2f;
    transform: translateY(-2px);
    box-shadow: 0 10px 25px rgba(229, 35, 55, 0.4);
}

.elementor-button:active {
    transform: translateY(0);
    box-shadow: 0 5px 15px rgba(229, 35, 55, 0.3);
}

/* Button Container */
.e-form__buttons {
    text-align: left;
}

/* Field Groups Spacing */
.elementor-field-group {
    margin-bottom: 0;
}

/* Required Field Indicator */
.elementor-field-required .elementor-field-textual {
    border-color: rgba(255, 255, 255, 0.2);
}

/* Error Messages */
.elementor-message-danger {
    background-color: rgba(229, 35, 55, 0.15);
    border-left: 4px solid #E52337;
    color: #ff6b7a;
    padding: 15px 20px;
    margin-top: 20px;
    border-radius: 6px;
}

/* Success Messages */
.elementor-message-success {
    background-color: rgba(76, 175, 80, 0.15);
    border-left: 4px solid #4caf50;
    color: #81c784;
    padding: 15px 20px;
    margin-top: 20px;
    border-radius: 6px;
}

/* Responsive Design */
@media (max-width: 768px) {
    .elementor-widget-form .elementor-form {
        padding: 40px 30px;
    }

    .elementor-field-group-name,
    .elementor-field-group-email {
        flex: 1 1 100%;
    }

    .elementor-field-textual {
        padding: 16px 20px;
        font-size: 14px;
    }

    .elementor-button {
        padding: 16px 40px;
        font-size: 14px;
        width: 100%;
        text-align: center;
    }

    textarea.elementor-field-textual {
        min-height: 150px;
    }
}

@media (max-width: 480px) {
    .elementor-widget-form .elementor-form {
        padding: 30px 20px;
    }

    .elementor-form-fields-wrapper {
        gap: 15px;
    }

    .elementor-field-textual {
        padding: 14px 18px;
    }

    .elementor-button {
        padding: 14px 30px;
        letter-spacing: 1.5px;
    }
}

/* Autofill Styling (Browser-Autofill dunkel halten) */
.elementor-field-textual:-webkit-autofill,
.elementor-field-textual:-webkit-autofill:hover,
.elementor-field-textual:-webkit-autofill:focus {
    -webkit-text-fill-color: #ffffff;
    -webkit-box-shadow: 0 0 0 1000px #2a2a2a inset;
    transition: background-color 5000s ease-in-out 0s;
    border: 2px solid rgba(255, 255, 255, 0.2);
}

/* Loading State */
.elementor-button.elementor-loading {
    opacity: 0.7;
    cursor: not-allowed;
}

/* Disabled State */
.elementor-field-textual:disabled {
    opacity: 0.5;
    cursor: not-allowed;
    background-color: #222222;
}
```

## Installation

1. Gehe zu **WordPress Dashboard → Customizer → Zusätzliches CSS**
2. Oder nutze ein Child-Theme und füge das CSS in die `style.css` ein
3. Oder bei Elementor: **Elementor → Custom CSS** (falls verfügbar)

## Anpassungen

- **Primärfarbe ändern**: Ersetze alle `#E52337` Werte
- **Border-Radius**: Passe die `border-radius` Werte an (aktuell 4px)
- **Abstände**: Ändere die `padding` und `margin` Werte nach Bedarf
