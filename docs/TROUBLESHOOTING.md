# Troubleshooting

## 🐛 Common Issues

1. **No Communication with Inverter**:
   - Check RS485 wiring (A+/B- connections)
   - Verify GPIO-settings are matching your hardware
   - Verify your flow control is en/disabled and the pin-configuration is matching your hardware
   - Ensure correct baud rate (9600 default)

2. **WiFi Connection Issues**:
   - Verify SSID and password in configuration
   - Check WiFi signal strength at ESP32 location
   - Use fallback hotspot for emergency access
   - Check router firewall settings

3. **Home Assistant Integration Problems**:
   - Verify API key matches between configuration and Home Assistant
   - Check ESPHome add-on logs for connection errors
   - Ensure ESPHome add-on is running and accessible
   - Verify network connectivity between devices

4. **Sensor Reading Issues**:
   - Check ESPHome device logs for Modbus errors
   - Verify inverter is powered and responsive
   - Check for electromagnetic interference near RS485 cables
   - Ensure proper grounding of RS485 converter

## Debug Mode

Enable verbose logging by uncommenting in `inverter-multi.yaml`:

logger:
  level: VERBOSE
```

Then check logs in ESPHome dashboard or Home Assistant ESPHome integration.
