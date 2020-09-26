# Face-Recognition

This program recognizes faces and names based on data provided by the user

## Requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/)

```bash
pip install -r requirements.txt
```

## Usage
Put data images to train on in known_faces folder along with the name of the person.

Put faces to analyze in unknown_faces folder

Uncomment train_faces() function to train on faces and then the program will attempt to recognize faces in unknown_faces folder

## Folder Structure

Face Recognition
├── known_faces/
│   └── name
│     └── images.png
├── unknown_faces/
│   └── imaes.png
└── facefinder.py

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
