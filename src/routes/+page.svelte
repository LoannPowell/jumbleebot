<script>
  import Input from "../lib/input/input.svelte";
  import ChatContainer from "../lib/chatContainer/chatContainer.svelte";
  import Message from "../lib/messages/message.svelte";
  import ButtonIcon from "../lib/buttonIcon/buttonIcon.svelte";
  import Header from "../lib/header/header.svelte";
  import Footer from "../lib/footer/footer.svelte";
  import "./global.css"
  import "./icon-font/style.css"
  import Loader from "../lib/loader/loader.svelte";
</script>
<Header name='Jumblee Bot' srcImage='https://cdn.midjourney.com/4227a7c0-8270-4cce-a6c5-5a5e062e0708/0_0.png'/>
<ChatContainer> 
  <Message sender={false} message='Hola Mundo!'/>
  <Message sender={true} message='Hola Mundo!'/>
</ChatContainer>
<Footer>
  <Input placeholder='Write your message' type='Test'/>
  <Loader/>
  <ButtonIcon>
    <span class="icon-send"></span>
  </ButtonIcon>
</Footer>

