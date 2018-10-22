# RNDemo-01
Presintation: https://docs.google.com/presentation/d/1BjiKXKonZIDzd2KSts2kLdwj7Zh6FW3UcFv5fK4QYDw/edit#slide=id.g3de0f6cb4a_1_10

1. Install watchmen using brew: https://brew.sh/
   
    ``` bash
    $ brew install watchman
    ```
    
2. Install expo-cli
    ```bash
    $ npm install -g expo-cli
    ```
    
3. Initialize a project
    ```bash
    $ expo init my-app
    ```
    
4. Run the project
    ```bash
    $ cd my-app
    $ npm start
    ```
5. Install NativeBase: https://docs.nativebase.io/docs/GetStarted.html
    ```bash
    $ yarn add native-base --save
    $ npm install @expo/vector-icons --save
    ```
6. Main Components from NativeBase: https://docs.nativebase.io/Components.html#Components
 
      ``` javascript
      <Container>
      
        <Header>
          <Body>
            <Title>
              Application
            </Title>
          </Body>
        </Header>
        
        <Content>
          <Button>
            <Text>Click me</Text>
          <Button>
        </Content>
        
        <Footer>
          <FooterTab>
            <Button full>
              <Text>Full footer button</Text>
            </Button>
          </FooterTab>
        </Footer>
        
      </Container>
      ```
      
      
