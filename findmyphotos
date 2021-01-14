import logging
import webbrowser
import requests

LOG_LEVEL = 'debug'

class PhotoFinder:
    def __init__(self, url='', photo_upload=None):
        self.url = url
        self.photo_upload = photo_upload
        self.log = ''
        self.logfile_dir = ''


    ## Processing photo methods
    def from_upload(self, image_name):
        # show the photo to user
        # prepare photo for method
        pass

    def from_url(self, image_name):
        pass


    ## Search the Photo (Make one work)
    # Maybe use Selenium
    def google_api_request_url(self):
        filePath = 'img/test.png'
        searchUrl = 'http://www.google.hr/searchbyimage/upload'
        multipart = {'encoded_image': (filePath, open(filePath, 'rb')), 'image_content': ''}
        response = requests.post(searchUrl, files=multipart, allow_redirects=False)
        fetchUrl = response.headers['Location']
        webbrowser.open(fetchUrl)
        pass

    def dummy_google_api_request(self):
        example_api_success = 'Write something here that\'s a real API output' # TODO
        example_api_fail = 'Write something here that\'s a real API output' # TODO
        
        return example_api_success
        pass

    def yahoo_api_request(self):
        pass

    def tineye_api_request(self):  # Not free
        pass

    def yandex_api_request(self):
        pass


    ## Return the Results
    def log_write(self, some_message=''):
        
        """
        ch = logging.basicConfig(filename='test.log', level=logging.DEBUG)
        formatter = logging.Formatter('%(asctime)s-%(name)s-%(levelname)s-%(message)s)
        
        ch.setFormatter(formatter)

      

        """
        """
        add new line to self.log with fields: date, time, severity, and message.
        default to debug level logging
        :return: boolean
        """

        

    def log_save(self):"""
        Attempt to save logfile to disk. 
        Make sure it doesn't conflict with previous saves
        :return: boolean
        """


    def print_info(self):
        print(self.url)
        print(self.photo_upload)


def results(self):
    pass

def main(**kwargs):
    url = kwargs['filename']
    filename = kwargs['url']
    pf = PhotoFinder(url, filename)
    pf.print_info()
    pf.log_write()


if __name__ == '__main__':
    main(url='google.com', filename='test.bmp')
