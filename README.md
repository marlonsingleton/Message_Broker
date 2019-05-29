### Message Broker Technology

# Azure Service Bus

**A highly reliable messaging service used to send information between decoupled applications and services.**

Asyncrhonous operation, FIFO, Publish/Subscribe Queue Capabilities

The C# BrokeredMessage Class

`public sealed class BrokeredMessage : IDisposable, System.Xml.Serialization.IXmlSerializable`

<ul>
Short List of Properties Include:
<li>ContentType
<li>Label
<li>MessageID
SequenceNumber
</ul>

Message is serialized and deserialized along with payload between application and services.
