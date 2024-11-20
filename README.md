# Ring buffer
Prety fast and simple implementation of Ring Buffer maded in a few week-ends primarly for own game engine.<br/>
Header-only , just drop into your project and include it.
## Use examples
![ExampleUsageRingBuffer](https://github.com/user-attachments/assets/81e00c04-2873-4ac0-9809-8a840c85657a)<br/>
NOTE* For declaration of RingBuffer you need to specify value type and allocator type.<br/>
If you don't want to use any specific allocators, you can use simple allocator defined within Ring Buffer header(just wrapper over malloc/free), just define RING_BUFFER_USE_SIMPLE_ALLOCATOR.

