# win-registry-snippets
Some snippets for Windows Registry that enchance User Experience

## WARNING

See WARNINGs in the files before importing/executing them

It is more safe to backup your registry before changes!



## If for current user only or no admin rights

The files in the repository applies changes to all users and needs the admin rights.

Although, you can easily modificate them to change only the current user and be able to executed without the admin rights.
Just replace all `HKEY_CLASSES_ROOT` with `HKEY_CURRENT_USER\Software\Classes`.

## How to apply the changes to the registry

### Way 1 (more suitable for the multiple files):
1. Download the .reg file(s) from this repository
2. Modificate the file(s) according to instructions in them and this document
  a. Right-click on the file
  b. Choose "Edit"
3. Open Registry Editor
  a. Open the "Run" window \[Win+R\]
  b. Type "regedit" in the text box
  c. Push the "Enter" keyboard button or "OK"
  d. Allow to make changes \[Choose "Yes"\]
4. In the top-left corner click on the "File" menu and choose the first "Import..." option
5. Choose the .reg file(s)

### Way 2:

After the second point of the first way just open the file as a usual file.
The system asks you to click on "Yes" twice, do it.

## Warranty

THIS SOFTWARE IS PROVIDED BY THE CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.