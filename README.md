# simplephpredirect
An example of a simple redirect made in PHP.

**PHP 301 Redirect**

This repository provides a simple solution to implement a 301 redirect using a PHP script. A 301 redirect is a permanent redirect that informs search engines and browsers that the requested resource has been permanently moved to a new location.

**How to Use**

1. **Create the Directory:**
Ensure that the directory you want to redirect (e.g., /test/) exists on your web server.

2. **Create the PHP Script:**
In the target directory (e.g., /test/), create an index.php file with the code presented in the example.

Replace https://example.com/new-location/ with the URL where you want to redirect visitors.

3. **Upload the File:**
Use an FTP client or your hosting panel to upload the index.php file to the desired directory (e.g., /test/).

4. **Test the Redirect:**
Visit the directory in your browser (e.g., https://example.com/test/) to ensure that it redirects correctly to the new location.

**Notes**

**Compatibility:** This solution works on any web server with PHP enabled.

**SEO-Friendly:** A 301 redirect informs search engines that the resource has permanently moved, helping maintain SEO rankings.

**Error Handling:** Ensure that the target URL is correct to avoid redirect loops or broken links.

**Example**

Suppose you want to redirect https://example.com/test/ to https://example.com/new-page/.

Create the directory /test/.

Add an index.php file with the code presented in the example.

Upload the file to your server.

Test the redirect by visiting https://example.com/test/.

**License**

This project is licensed under the MIT License. Feel free to use and modify as needed.
