# Deserializer

This script is meant to deserialize data that was collected during a simulated Driver/Pedestrian study at Cornell Tech.

It simply takes a folder of csvfiles (delimiter=';') with the serialized data, and uses pandas, base64 and struct libraries to create a copy of each file with each cell being replaced with the deserialized version.
