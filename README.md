
  The purpose of this code is to generate a random password based on user input to define the parameters. The default parameter for the user is just 
  lowercase characters. The other three include capitalized characters, numbers, and special characters. This allows the user to define the parameters in
  any combination of those three with the default. The script will auto export the password as a plaintext document titled "Avocado.txt". From there
  the user has the option to encrypt the password(see below) and decrypt the password.
  
  Note: All passwords generator will be stored as a plaintext document in the same storage location as where the script is located. In order for the
  encyrption and decryption process to function properly the documents must utilize that naming convention.
  
  Encryption key:
  In order to use Fernet to generate a key and perform the encrypt and decrypt tools cryptography must first be installed. To install see below:
  from teminal enter the following: pip install cryptography  
  Using my key generation code the key will be named "avocado_pit.key" and will require that naming convention for the password generation script. 
