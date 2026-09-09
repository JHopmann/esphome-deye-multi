# ESPHome Deye Multiple Inverter

<!--
Copyright 2025 Lewa-Reka <lewareka.yt@gmail.com>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

![Maintenance](https://img.shields.io/maintenance/yes/2026?style=for-the-badge)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/lewa-reka/esphome-deye-inverter/build-ci.yaml?style=for-the-badge)
![GitHub License](https://img.shields.io/github/license/lewa-reka/esphome-deye-inverter?style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/lewa-reka/esphome-deye-inverter?style=for-the-badge)

An ESPHome-based solution for monitoring and controlling Deye photovoltaic inverters via Modbus RTU communication. This project provides comprehensive integration with Home Assistant, enabling real-time monitoring and control of solar power systems.

For an excellent overview of the features and installation watch the video from the author of the original project (Lewa-Reka)
Installation & Presentation: https://youtu.be/iJjsA_MzmnE 

## 📚 Documentation

- **[Supported Devices](docs/SUPPORTED_DEVICES.md)**: List of supported inverters and specific configurations.
- **[Register-Documentation](docs/Deye.Modbus.protocol.V118.pdf)**: Original DEYE modbus documentation.
- **[Features & Capabilities](docs/FEATURES.md)**: Detailed overview of features, safety mechanisms, and monitoring capabilities.
- **[Installation Guide](docs/INSTALLATION.md)**: Hardware requirements, wiring diagrams, and step-by-step installation instructions.
- **[Configuration](docs/CONFIGURATION.md)**: Configuration options, parameters, and update instructions.
- **[Troubleshooting](docs/TROUBLESHOOTING.md)**: Common issues and solutions.
- **[Contributing](docs/CONTRIBUTING.md)**: Guidelines for contributing to the project.

## 📄 License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

### Copyright Notice

```
Copyright 2025 Lewa-Reka <lewareka.yt@gmail.com>

Modifications Copyright 2026 JHopmann <Joerg@Hopmann.name>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
### BASIS (Fork/History)

This project is based on a fork from the original deye inverter project created by Lewa-Reka (https://github.com/Lewa-Reka/esphome-deye-inverter).
Forked on August 21, 2026

This project is intended to extend the work of Lewa-Reka to connect multiple inverters to one single ESP32-instance.

### Third-Party Components

This project uses ESPHome and related components. Please refer to the [NOTICE](NOTICE) file for additional license information.

## 🙏 Acknowledgments

- [Deepseek Chatbot](https://chat.deepseek.com/) Nicknamed "Deepy" for his patience with me regarding my sometimes rambling questions.
- [ESPHome Team](https://esphome.io/) for the excellent home automation platform
- [Home Assistant Community](https://community.home-assistant.io/) for continuous support and inspiration

## 📞 Support

- **GitHub Issues**: [Report bugs or request features](https://github.com/JHopmann/esphome-deye-multi/issues)
- **Home Assistant Community**: [ESPHome section](https://community.home-assistant.io/c/esphome/) for general ESPHome help

## 🔗 Related Projects

- [ESPHome Official Docs](https://esphome.io/) - ESPHome documentation

---

**⚠️ Disclaimer**: This project is not officially affiliated with Deye. Use at your own risk and ensure compliance with local electrical codes and regulations. Always consult with a qualified electrician for installation and safety verification. The authors are not responsible for any damage to equipment or injury resulting from the use of this software.
